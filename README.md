Less Compiler Plugin for Mecha CMS
==================================

> `lessphp` is a compiler for Less written in PHP.

**lessphp** is a compiler that generates CSS from a superset language which
adds a collection of convenient features often seen in other languages. All CSS
is compatible with Less, so you can start using new features with your existing CSS.

It is designed to be compatible with [less.js](http://lesscss.org), and suitable
as a drop in replacement for PHP projects.

The home page for **lessphp** can be found at <http://leafo.net/lessphp>

---

#### Less Asset

Use it as the way you use `Asset::stylesheet()`.

~~~ .php
echo Asset::less('path/to/file.less');
~~~