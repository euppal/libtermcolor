# Usage

Use the following character (sequences) and _only_ them within a left and right bracket to construct valid colors.

### Foreground Colors

Character | Name
--------- | ----
`N`       | Black
`R`       | Red
`G`       | Green
`Y`       | Yellow
`B`       | Blue
`M`       | Magenta
`C`       | Cyan
`W`       | White

### Background Colors

Same as foreground colors, but prefixed with `,`, i.e. `,R`, `,Y`, `,W`. This mimics the behavior in Nano.

### Formatting

Character | Name
--------- | ----
`+`       | Bold
`-`       | Faint
`_`       | Underline
`*`       | Blink
`~`       | Strikethrough

### Examples

Example  | Description
-------- | ----
`{R}`    | Normal red
`{+-B}`  | Bold and faint blue
`{_*,G}` | Underlined blinking with green background
`{Y,C}`  | Yellow with cyan background
`{W~}`   | Normal white with strikethrough

### Complete Syntax

The full syntax for colors can be found in [`syntax.ebnf`](syntax.ebnf).