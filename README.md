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

* `thicol` => http://thi.ng/color namespaces
* `thicl` => http://thi.ng/simplecl namespaces
* `thifab` => http://thi.ng/fabric namespaces (all modules)
* `thigeom` => http://thi.ng/geom namespaces (all modules)
* `thilux` => http://thi.ng/luxor namespaces
* `thimath` => http://thi.ng/math namespaces
* `thitrio` => http://thi.ng/trio namespaces

### thi.ng/color specific snippets

* `csscol` => convert color to CSS string
* `cosgradient` => cosine gradient gen (with preset chooser)

### thi.ng/geom specific snippets

(Targets latest API state in dev-branch)

* `exportmesh` (with type chooser) => export mesh in different formats
* `importmesh` => import mesh (currently STL only)
* `ptfmesh` => convert point seq to bezier to [PTF mesh](https://github.com/thi-ng/geom/blob/master/geom-types/src/ptf.org)
* `txmat` => 4x4 transform matrix (translate, rotate, scale)
