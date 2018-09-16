# Group Therapy Land

# Creativerse Teleportation Codes

## Introduction

Learn about `Teleporter`s in [Creativerse Wikia][creativerse-wikia].

## Reserved codes

Codes that contain `Teleporter` or *empty* slots SHOULD NOT be generally used 
and they are considered reserved.

### Closed Teleportation Terminals

#### Null Teleporter Code

`*Empty*`, `Stone`, `*Empty*`

A teleporter with this code is used only for departures. This code SHOULD NOT be used as teleporter destination.

#### Null Teleporter Destination

`Stone`, `*Empty*`, `Stone`

A teleporter with this destination is used only for arrivals. This code SHOULD NOT be used as teleporter code.


## The Central Teleportation Station (CTS)

|      | Slot 1       | Slot 2  | Slot 3           |
| :--  | :--          | :--     | :--              |
| Code | `Teleporter` | `Stone` | `Teleporter`     |

There is a central teleportation station (CTS) that may host teleporters to various 
destinations such as global access points, named biomes etc.

Access to the teleportation station is free. If you want to access the station, 
create a teleporter (plus two more, as required by the code) at the site of your 
preference and add the aforementioned code as destination.

## Destinations Catalogue

### Sites

| Location               | Slot 1       | Slot 2            | Slot 3               | CTS Terminal |
| :--                    | :--              | :--               | :--              | :--          |
| Earendil's Arena       | `Iron Ore`       | `Obsidian Ore`    | `Gunpowder`      | Yes          |
| Lab Farm (Surface)     | `Wood Fence`     | `Shredded Leaves` | `Wheat`          | Yes          |
| Lab Farm (Underground) | `Wood Fence`     | `Bedrock`         | `Limestone Wall` | No           |
| Lokahiou's Water Park  | `Ice`            | `Water`           | `Grass`          | Yes          |
| Sky Temple (CTS)       | `Teleporter`     | `Stone`           | `Teleporter`     | -            |
| Zakarum Fjord Keep     | `Stone`          | `Stone`           | `Stone`          | Yes          |
| Zakarum Keep Lab       | `Miru Eye`       | *Empty*           | `Bedrock`        | No           |
| Project: "Moria"       | `Stone`          | `Bedrock`         | `Hardened Lava`  | No           |
| Project: "Sphere"      | `Galactic Hull`  | `Galactic Hull`   | `Galactic Hull`  | No           |

### Named Biomes

| Location               | Slot 1       | Slot 2            | Slot 3           | CTS Terminal |
| :--                    | :--          | :--               | :--              | :--          |
| Whiterock Mountains    | `Snow`       | `Snow`            | `Rambeau Tuft`   | Yes          |
| Five-wood Station      | `Wildwood`   | `Weepwood`        | `Shorewood`      | Yes          |
| Apophis Desert         | `Sand`       | `Sand`            | `Cactus Flower`  | Yes          |

### Global Teleportation System

#### Global Compass Points

| Location                | Slot 1       | Slot 2            | Slot 3           | CTS Terminal |
| :--                     | :--          | :--               | :--              | :--          |
| Global Center           | `Teleporter` | `Teleporter`      | `Teleporter`     | Yes          |
| Global North            | `Teleporter` | `Teleporter`      | `Snow`           | Yes          |
| Global West             | `Teleporter` | `Teleporter`      | `Canyonstone`    | Yes          |
| Global East             | `Teleporter` | `Teleporter`      | `Detritus`       | Yes          |
| Global South *Inactive* | `Teleporter` | `Teleporter`      | `Sand`           | No           |

#### Continental Compass Points

| Location                   | Slot 1       | Slot 2            | Slot 3           | CTS Terminal |
| :--                        | :--          | :--               | :--              | :--          |
| Continent West             | `Teleporter` | `Wood Ladder`     | `Canyonstone`    | Yes          |
| Continent East             | `Teleporter` | `Wood Ladder`     | `Dentritus`      | Yes          |
| Continent South            | `Teleporter` | `Wood Ladder`     | `Sand`           | Yes          |
| Continent North *Inactive* | `Teleporter` | `Wood Ladder`     | `Snow`           | No           |


## Per site

### Zakarum Fjord Keep

| Location                   | Slot 1       | Slot 2            | Slot 3                | CTS Terminal | Bidirectional |
| :--                        | :--          | :--               | :--                   | :--          | :--           |
| Keep's roof                | `Stone`      | `Stone`           | `Medieval Brick Wall` | No           | Yes           |
| Keep's Lab farm            | `Bedrock`    | *Empty*           | `Miru Eye`            | No           | Yes           |
| Keep's Pool Jump           | `Stone`      | `Stone`           | `Water`               | No           | No            |

### Lokahiou's Fun Park

| Location                   | Slot 1       | Slot 2            | Slot 3                | CTS Terminal | Bidirectional |
| :--                        | :--          | :--               | :--                   | :--          | :--           |
| High column                | `Sand`       | `Sand`            | `Grass`               | No           | Yes           |


## Teleportation coding conventions

### Directional Prefices

| Location                   | Slot 1       | Slot 2            | Slot 3                |
| :--                        | :--          | :--               | :--                   |
| Global                     | `Teleporter` | `Teleporter`      | *any*                 |
| Continental                | `Teleporter` | `Wood Ladder`     | *any*                 |

### Directional Suffices

| Location                   | Slot 1       | Slot 2            | Slot 3                |
| :--                        | :--          | :--               | :--                   |
| North                      | *any*        | *any*             | `Snow`                |
| West                       | *any*        | *any*             | `Canyonstone`         |
| East                       | *any*        | *any*             | `Dentritus`           |
| South                      | *any*        | *any*             | `Sand`                |

### Biome Prefices

| Location                   | Slot 1       | Slot 2            | Slot 3                |
| :--                        | :--          | :--               | :--                   |
| Snow Mountain              | `Snow`       | `Snow`            | *any*                 |
| Dunes                      | `Sand`       | `Sand`            | *any*                 |



 [creativerse-wikia]: http://creativerse.wikia.com/wiki/Teleporter