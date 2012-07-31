# VIM & Ruby language definitions for Prism

Add support for Ruby & Vim languages to Prism.js highlighter (http://primjs.com).

## Usage

Just load the language you want after prism.js and define the additional classes in your stylesheet.

```html
<script src="js/prism.min.js" type="text/javascript"></script>
<script src="js/prism.ruby.js" type="text/javascript"></script>
<script src="js/prism.vim.js" type="text/javascript"></script>
```

```css
.token.attr-value { ... }
.token.builtin { ... }
.token.const { ... }
.token.symbol { ... }
```

## License

This program is free software. It comes without any warranty, to
the extent permitted by applicable law. You can redistribute it
and/or modify it under the terms of the Do What The Fuck You Want
To Public License, Version 2, as published by Sam Hocevar. See
http://sam.zoy.org/wtfpl/COPYING for more details.
