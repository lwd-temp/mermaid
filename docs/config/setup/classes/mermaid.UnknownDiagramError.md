> **Warning**
>
> ## THIS IS AN AUTOGENERATED FILE. DO NOT EDIT.
>
> ## Please edit the corresponding file in [/packages/mermaid/src/docs/config/setup/classes/mermaid.UnknownDiagramError.md](../../../../packages/mermaid/src/docs/config/setup/classes/mermaid.UnknownDiagramError.md).

# Class: UnknownDiagramError

[mermaid](../modules/mermaid.md).UnknownDiagramError

## Hierarchy

- `Error`

  ↳ **`UnknownDiagramError`**

## Constructors

### constructor

• **new UnknownDiagramError**(`message`): [`UnknownDiagramError`](mermaid.UnknownDiagramError.md)

#### Parameters

| Name      | Type     |
| :-------- | :------- |
| `message` | `string` |

#### Returns

[`UnknownDiagramError`](mermaid.UnknownDiagramError.md)

#### Overrides

Error.constructor

#### Defined in

[packages/mermaid/src/errors.ts:2](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/errors.ts#L2)

## Properties

### cause

• `Optional` **cause**: `unknown`

#### Inherited from

Error.cause

#### Defined in

node_modules/.pnpm/typescript\@5.4.5/node_modules/typescript/lib/lib.es2022.error.d.ts:24

---

### message

• **message**: `string`

#### Inherited from

Error.message

#### Defined in

node_modules/.pnpm/typescript\@5.4.5/node_modules/typescript/lib/lib.es5.d.ts:1077

---

### name

• **name**: `string`

#### Inherited from

Error.name

#### Defined in

node_modules/.pnpm/typescript\@5.4.5/node_modules/typescript/lib/lib.es5.d.ts:1076

---

### stack

• `Optional` **stack**: `string`

#### Inherited from

Error.stack

#### Defined in

node_modules/.pnpm/typescript\@5.4.5/node_modules/typescript/lib/lib.es5.d.ts:1078

---

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`\[]) => `any`

Optional override for formatting stack traces

**`See`**

<https://v8.dev/docs/stack-trace-api#customizing-stack-traces>

#### Type declaration

▸ (`err`, `stackTraces`): `any`

##### Parameters

| Name          | Type          |
| :------------ | :------------ |
| `err`         | `Error`       |
| `stackTraces` | `CallSite`\[] |

##### Returns

`any`

#### Inherited from

Error.prepareStackTrace

#### Defined in

node_modules/.pnpm/@types+node\@20.16.11/node_modules/@types/node/globals.d.ts:98

---

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

Error.stackTraceLimit

#### Defined in

node_modules/.pnpm/@types+node\@20.16.11/node_modules/@types/node/globals.d.ts:100

## Methods

### captureStackTrace

▸ **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name              | Type       |
| :---------------- | :--------- |
| `targetObject`    | `object`   |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

Error.captureStackTrace

#### Defined in

node_modules/.pnpm/@types+node\@20.16.11/node_modules/@types/node/globals.d.ts:91