language-glacia
===============

Adds support for syntax highlighting glacia code
(https://github.com/briansteffens/glacia) to Atom.

This is nowhere near complete, this was pretty much copied straight from the C
language highlighter (https://github.com/atom/language-c) with little changed
so far.

To install, clone it:

```
$ git clone https://github.com/briansteffens/language-glacia
```

Then symlink it so Atom will see it:

```
$  ln -nsf `pwd`/language-glacia ~/.atom/packages/
```

Now you should be able to reload any Atom instances (Ctrl+Shift+P, "reload",
enter) to see the changes.
