<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# EightSideRoom

**Extends:** [Node2D](../Node2D)

## Description

A scene, that can be instantiated in a scene and features a room
with up to eight different sides with automatic view navigation using a Camera2D

## Constants Descriptions

### TEXTURE\_DISTANCE

```gdscript
const TEXTURE_DISTANCE: int = 100
```

Distance between textures to allow overlapping hotspot areas

### VIEW\_BACK

```gdscript
const VIEW_BACK: String = "back"
```

### VIEW\_BACKLEFT

```gdscript
const VIEW_BACKLEFT: String = "backleft"
```

### VIEW\_BACKRIGHT

```gdscript
const VIEW_BACKRIGHT: String = "backright"
```

### VIEW\_FRONT

```gdscript
const VIEW_FRONT: String = "front"
```

### VIEW\_FRONTLEFT

```gdscript
const VIEW_FRONTLEFT: String = "frontleft"
```

view constants

### VIEW\_FRONTRIGHT

```gdscript
const VIEW_FRONTRIGHT: String = "frontright"
```

### VIEW\_LEFT

```gdscript
const VIEW_LEFT: String = "left"
```

### VIEW\_RIGHT

```gdscript
const VIEW_RIGHT: String = "right"
```

### VIEW\_UNSET

```gdscript
const VIEW_UNSET: String = ""
```

An unset view

## Property Descriptions

### view\_dict

```gdscript
var view_dict
```

Dictionary used to map view constant to index (and back)

### default\_view

```gdscript
export var default_view = "front"
```

The default/starting view of the four views

### frontleft\_texture

```gdscript
export var frontleft_texture = "[Object:null]"
```

The texture for the front view

### front\_texture

```gdscript
export var front_texture = "[Object:null]"
```

### frontright\_texture

```gdscript
export var frontright_texture = "[Object:null]"
```

### right\_texture

```gdscript
export var right_texture = "[Object:null]"
```

### backright\_texture

```gdscript
export var backright_texture = "[Object:null]"
```

### back\_texture

```gdscript
export var back_texture = "[Object:null]"
```

### backleft\_texture

```gdscript
export var backleft_texture = "[Object:null]"
```

### left\_texture

```gdscript
export var left_texture = "[Object:null]"
```

### current\_view

```gdscript
var current_view
```

The current view shown to the player

## Signals

- signal view_changed(old_view, new_view): Triggered when the user switches the view
