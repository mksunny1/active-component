**active-component** • [**Docs**](globals.md)

***

# Active Component

This is a simple, composable and extensible library for creating reactive web interfaces. It exports primitives which can be used to describe DOM operations with element attributes. It is based on the [class-action](https://github.com/mksunny1/class-action) and [action-object](https://github.com/mksunny1/action-object) libraries.

An active component is a ClassAction sub-type that recursively processes elements to interprete attribute directives. Other class actions (known as component actions) are nested within the active component to perform the interpretative functions. This affords enormous flexibility in what meanings can be attached to directives. Component actions for most common functions, like linking element properties to javascript variables, have been implemented. Further actions may be created by 3rd-party providers or users themselves.

## Installation

`npm i active-component`

## Usage

```html
<h1>#a</h1>
<main>#b</main>
```

```js
import { ActiveComponent } from "active-component";
import { ActionObject } from "active-object";
const root = new ActionObject({ a: 'Heading', b: 'This is the content' });
const activeComponent = new ActiveComponent();
activeComponent.act({element: document.body, root})
```

## Documentation

This library exports class actions for many common reactive actions, like data binding and array rendering. Learn about them [here](). 

* Note: Both the docs and the tests are still works in progress ATM.

## Contributing

Help improve Active-component by contributing to this project. You can contribute in many ways. See the [contributing guidelines](). You can also show your support by sponsoring us.

[![](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=S2ZW3RJSDHASW)

Thank you for contributing.

## Sponsors

...
