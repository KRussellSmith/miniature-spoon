A text function for HTML canvas (to compensate for the limited nature of fillText())

Surround bold text with astericks, italic with underscores.
Use the carriage return ('\r') to switch to the next color (or wrap around to the first)

Arguments:
 1. ctx: the _CanvasRenderingContext2D_ to which you want to render
 1. text: the _string_ to render
 1. x: _number_
 1. y: _number_
 1. { font?: _string_; spacing?: the _number_ of pixels between lines }
 1. ...colors: _strings_ representing web colors, iterated via '\r'
