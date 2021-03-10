Ellipsis Title
==============

Put `title` attribute to elements that have `text-overflow: ellipsis`


SYNOPSIS
--------

A ellipsis-ed element should have `title` attribute, and this value should be
same as its content. However, we are too busy to write `title` attributes! This
library adds `title` attributes automatically to every element that have
`text-overflow: ellipsis`.


USAGE
-----

Put `dist/ellipsis-title.js` into `head` element of your HTML document.

```html
<script defer src="/js/ellipsis-title.js"></script>
```

Don’t forget `defer` attribute!


LICENSE
-------

MIT
