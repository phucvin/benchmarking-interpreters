cd ..

go build

./bi tests/fib.lisp --mode ast

./bi tests/fib.lisp --mode vm
