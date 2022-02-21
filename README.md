## Steps to reproduce the error

Generate `AST.cmi` and `AST.cmo` by `ocamlfind ocamlc -c AST.ml`

`menhir --explain --inspection --table --dump --infer parser.mly` returned `Error: Unbound module Sedlexing`
