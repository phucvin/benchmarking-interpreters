cd ..

go build

./bi tests/fib.lisp --mode ast

./bi tests/fib.lisp --mode vm

./bi test/t01.lisp --mode ast

TODO: make `let` work in vm mode
./bi test/t01.lisp --mode vm
