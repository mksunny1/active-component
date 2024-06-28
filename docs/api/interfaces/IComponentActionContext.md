[**active-component**](../README.md) • **Docs**

***

[active-component](../globals.md) / IComponentActionContext

# Interface: IComponentActionContext

## Properties

### closedElement?

> `optional` **closedElement**: `boolean`

Whether to not process the element further.

#### Defined in

src/component/component-action.ts:30

***

### element

> **element**: `Element`

The current element being processed in the component-action.

#### Defined in

src/component/component-action.ts:10

***

### parent?

> `optional` **parent**: [`IComponentActionContext`](IComponentActionContext.md)

Optional parent context.

#### Defined in

src/component/component-action.ts:15

***

### reactionKey?

> `optional` **reactionKey**: `string`

Optional key for adding actions to the roots

#### Defined in

src/component/component-action.ts:20

***

### root

> **root**: `ActionObject`

The component action

#### Defined in

src/component/component-action.ts:25
