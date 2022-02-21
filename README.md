## Steps to reproduce where we are stuck

Generate `AST.cmi` and `AST.cmo` by `ocamlfind ocamlc -c AST.ml`

Then, `menhir --explain --inspection --table --dump --infer parser.mly` returned `Error: Unbound module Sedlexing`
