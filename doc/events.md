# API Events

## `load`

Fired when a panorama finishes loading.


## `scenechange`

Fired when a scene change is initiated. A `load` event will be fired when the
new scene finishes loading. Passes scene ID string to handler.


## `scenechangefadedone`

If a scene transition fade interval is specified, this event is fired when the
fading is completed after changing scenes.


## `error`

Fired when an error occured. The error message string is passed to the
event listener.


## `errorcleared`

Fired when an error is cleared.


## `mousedown`

Fired when the mouse button is pressed. Passes `MouseEvent` to handler.


## `mouseup`

Fired when the mouse button is released. Passes `MouseEvent` to handler.
