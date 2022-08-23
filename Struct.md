# Structs
* [World](#World)
* [WorldObject](#worldobject)
* [NetAvatar](#netavatar)
* [Tile](#tile)
* [InventoryItem](#inventoryitem)
* [GamePacket](#gamepacket)
* [ItemInfo](#iteminfo)
* [VariantList](#variantlist)

## WorldObject
| Type | Name | Description|
|:-----|:----:|:-----------|
| Number | `id` | Object's item ID |
| Number | `oid` | Object's index |
| Number | `x` | Players's Pos X |
| Number | `y` | Players's Pos Y |
| Number | `count` | Object's item count |
| Number | `flags` | Object's flags |
 
 ## NetAvatar
| Type | Name | Description|
|:-----|:----:|:-----------|
| String | `name` | Player's name |
| Number | `netId` | Player's netID |
| Number | `userId` | Player's userID |
| Number | `x` | Players's Pos X |
| Number | `y` | Players's Pos Y |


 ## Tile
| Type | Name | Description|
|:-----|:----:|:-----------|
| Number | `fg` | Foreground block's ID |
| Number | `bg` | Background block's ID |
| Number | `x`  | Position x |
| Number | `y`  | Position y |
| Boolean | `isSolid` | Tile's Solid block |
| Number | `ready` | Tile's Ready |

 ## World
| Type | Name | Description|
|:-----|:----:|:-----------|
| string | `name` | World's Name |
| Number | `width` | World's width |
| Number | `tileCount`  | Position x |
| Number | `objectCount`  | Position y |
| Boolean | `isSolid` | Tile's Solid block |
| Number | `ready` | Tile's Ready |

 ## InventoryItem
| Type | Name | Description|
|:-----|:----:|:-----------|
| Number | `id` | Item's ID |
| Number | `count` | Item count |


## GamePacket
| Type | Name | Description|
|:-----|:----:|:-----------|
| Number | `type` | Packet type |
| Number | `objType` |  |
| Number | `count ` |  |
| Number | `count2 ` |  |
| Number | `flags ` | |
| Number | `item ` |  |
| Number | `flags ` | Packet flags |
| Number | `float` |  |
| Number | `intData` |  |
| Number | `posX` |  |
| Number | `posY` |  |
| Number | `pos2X` |  |
| Number | `pos2Y` |  |
| Number | `float2` |  |
| Number | `tileX` |  |
| Number | `tileY` |  |
| Number | `size` |  |
| Number | `data` |  |

## ItemInfo
| Type | Name | Description|
|:-----|:----:|:-----------|
| String | `name` | Item name |
| Number | `id` | Item ID |
| Number | `rarity` | Item rarity |
| Number | `growTime` | Item growtime |
| Number | `breakHits` | Item breakhits |
| Number | `collisionType` | Item Collision Type |
| Number | `type` | Item Type |

## VariantList
| Type | Name | Description|
|:-----|:----:|:-----------|
| String | `var[0]` | Variant function name |
| String | `var[1]` | Param 1 |
| String | `var[2]` | Param 2 |
| String | `var[3]` | Param 3 |
| String | `var[4]` | Param 4 |
| String | `var[5]` | Param 5 |

Credit [Arky](https://github.com/arky-arky/teohook-scripting-wrapper)
