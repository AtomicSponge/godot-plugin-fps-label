# Godot FPS Label Plugin
A simple plugin that adds a FPS counter.

## How it Works
Add the plugin to your project then create a keymap called `fps` and assign the key you want to display and hide the FPS counter with.  Then add the FPS counter node into your project.  It inherits from a `Label` type so you will want to add it to a CanvasLayer for it to say in position.

## API Reference
- `show_fps() -> void`:  Show the FPS counter.

- `hide_fps() -> void`:  Hide the FPS counter.
