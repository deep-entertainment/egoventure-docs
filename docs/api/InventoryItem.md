<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# InventoryItem

**Extends:** [Resource](../Resource)

## Description

An inventory item

## Property Descriptions

### title

```gdscript
export var title: String = ""
```

The title of the inventory item

### description

```gdscript
export var description: String = ""
```

A description for the inventory item

### image\_normal

```gdscript
export var image_normal: Texture = "[Object:null]"
```

The image/mouse pointer for the inventory item

### image\_active

```gdscript
export var image_active: Texture = "[Object:null]"
```

The image/mouse pointer for the inventory item if it's selected

### image\_big

```gdscript
export var image_big: Texture = "[Object:null]"
```

The big image used in detail views

### combineable\_with

```gdscript
export var combineable_with: Array = []
```

The items this item can be combined with

### detail\_scene

```gdscript
export var detail_scene: String = ""
```

A scene to load for the detail view instead of the big image

### detail\_show\_mouse

```gdscript
export var detail_show_mouse: bool = false
```

Whether to show the mouse cursor in the detail view

### grabbable

```gdscript
export var grabbable: bool = true
```

Whether the item is selectable and useable on the screen
If set to false, clicking the item with either mouse button will show the
(custom) detail view