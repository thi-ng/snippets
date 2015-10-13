# thi.ng/snippets

Growing [yasnippet](https://github.com/capitaomorte/yasnippet) code
snippet collection for various thi.ng libraries:

## Installation

```
cd ~/.emacs.d
git clone git@github.com:thi-ng/snippets.git thing-snippets
```

Then add directory to yasnippet search paths (in `init.el`):

```emacs-lisp
(add-to-list 'yas-snippet-dirs "~/.emacs.d/thing-snippets")
```

## Available snippets

### Namespace choosers

Useful for importing various thi.ng lib namespaces in a `:require` spec:

* `thicol` => thi.ng/color namespaces
* `thicl` => thi.ng/simplecl namespaces
* `thifab` => thi.ng/fabric namespaces (all modules)
* `thigeom` => thi.ng/geom namespaces (all modules)
* `thilux` => thi.ng/luxor namespaces
* `thimath` => thi.ng/math namespaces
* `thitrio` => thi.ng/trio namespaces

