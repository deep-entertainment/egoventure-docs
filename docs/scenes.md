# Scenes and navigation

## Scenes

While the player moves around in the game, each view is made up of a Godot scene that contains [Hotspots](hotspots.md) which trigger code that changes the current scene.

This makes designing a game straight forward.

## Caching of scenes

Because changing scenes - especially with large images - takes time, *EgoVenture* supports scene caching that preloads upcoming scenes in the background. Details can be found in the [Cache](cache.md) documentation

## Four-Side-Room scenes

Since most of the scenes that the player walks through, consist of a front, right, left and back view, *EgoVenture* includes a helper scene `four_side_room.tscn`, that can be instantiated in a scene to speed up creating walk-throughs.

After instantiating it in the specific scene, it can be configured which images will be displayed on the four sides.

The four sides will be shown around the center like a cut-open box.

The scene will take care of showing the images and navigating left and right.

Additional hotspots (e.g. for moving forward) can be placed over the four sides.

## Eight-Side-Room scenes

`eight_side_room.tscn` is another helper scene similar to Four-Side-Room. Main difference is that it allows up to 8 views around the center.

After instantiating it in the specific scene, it can be configured which images will be displayed on the eight sides. Sides can remain empty. This means this helper scene can also be used to build for example a room with three sides or six sides.