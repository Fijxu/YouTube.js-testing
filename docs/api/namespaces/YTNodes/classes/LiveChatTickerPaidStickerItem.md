[youtubei.js](../../../README.md) / [YTNodes](../README.md) / LiveChatTickerPaidStickerItem

# Class: LiveChatTickerPaidStickerItem

## Extends

- [`YTNode`](../../Helpers/classes/YTNode.md)

## Constructors

### new LiveChatTickerPaidStickerItem()

> **new LiveChatTickerPaidStickerItem**(`data`): [`LiveChatTickerPaidStickerItem`](LiveChatTickerPaidStickerItem.md)

#### Parameters

• **data**: [`RawNode`](../../APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`LiveChatTickerPaidStickerItem`](LiveChatTickerPaidStickerItem.md)

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`constructor`](../../Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:23](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L23)

## Properties

### author\_external\_channel\_id

> **author\_external\_channel\_id**: `string`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:10](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L10)

***

### author\_photo

> **author\_photo**: [`Thumbnail`](../../Misc/classes/Thumbnail.md)[]

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:11](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L11)

***

### duration\_sec

> **duration\_sec**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:14](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L14)

***

### end\_background\_color

> **end\_background\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:13](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L13)

***

### full\_duration\_sec

> **full\_duration\_sec**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:15](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L15)

***

### id

> **id**: `string`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:9](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L9)

***

### show\_item

> **show\_item**: [`YTNode`](../../Helpers/classes/YTNode.md)

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:16](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L16)

***

### show\_item\_endpoint

> **show\_item\_endpoint**: [`NavigationEndpoint`](NavigationEndpoint.md)

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:17](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L17)

***

### start\_background\_color

> **start\_background\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:12](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L12)

***

### ticker\_thumbnails

> **ticker\_thumbnails**: `object`[]

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:18](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L18)

***

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/helpers.ts#L8)

***

### type

> `static` **type**: `string` = `'LiveChatTickerPaidStickerItem'`

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts:7](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/classes/livechat/items/LiveChatTickerPaidStickerItem.ts#L7)

## Methods

### as()

> **as**\<`T`, `K`\>(...`types`): `InstanceType`\<`K`\[`number`\]\>

Cast to one of the given types.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The types to cast to

#### Returns

`InstanceType`\<`K`\[`number`\]\>

The node cast to one of the given types

#### Throws

If the node is not of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`as`](../../Helpers/classes/YTNode.md#as)

#### Defined in

[src/parser/helpers.ts:29](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/helpers.ts#L29)

***

### hasKey()

> **hasKey**\<`T`, `R`\>(`key`): `this is LiveChatTickerPaidStickerItem & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is LiveChatTickerPaidStickerItem & { [k in string]: R }`

Whether the node has the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`hasKey`](../../Helpers/classes/YTNode.md#haskey)

#### Defined in

[src/parser/helpers.ts:41](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/helpers.ts#L41)

***

### is()

> **is**\<`T`, `K`\>(...`types`): `this is InstanceType<K[number]>`

Check if the node is of the given type.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The type to check

#### Returns

`this is InstanceType<K[number]>`

whether the node is of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`is`](../../Helpers/classes/YTNode.md#is)

#### Defined in

[src/parser/helpers.ts:19](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/helpers.ts#L19)

***

### key()

> **key**\<`T`, `R`\>(`key`): [`Maybe`](../../Helpers/classes/Maybe.md)

Assert that the node has the given key and return it.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

[`Maybe`](../../Helpers/classes/Maybe.md)

The value of the key wrapped in a Maybe

#### Throws

If the node does not have the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`key`](../../Helpers/classes/YTNode.md#key)

#### Defined in

[src/parser/helpers.ts:51](https://github.com/LuanRT/YouTube.js/blob/e1650e12979e68b9546bc63989f86b651960a10a/src/parser/helpers.ts#L51)
