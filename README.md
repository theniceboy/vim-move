# move lines

Normal:

    <A-e>   Move current line/selection up
    <A-u>   Move current line/selection down

Visual:

    <A-l>   Move current line/selection up
    <A-y>   Move current line/selection down

![vim-vertical-move demo](http://i.imgur.com/RMv8KsJ.gif)

## Customization

Use `g:move_key_modifier` to set a custom modifier for key bindings. For
example,

```vim
let g:move_key_modifier = 'C'
```

which will make the modifier the control key

Normal:

    <C-e>   Move current line/selection up
    <C-u>   Move current line/selection down

Visual:

    <C-l>   Move current line/selection up
    <C-y>   Move current line/selection down

And so on...

## License

This plugin is licensed under MIT license.
