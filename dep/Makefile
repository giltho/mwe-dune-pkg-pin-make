build: libfile
	dune build

libfile:
	echo "let f () = print_endline \"Hello, world!\"" > lib/dep.ml
	
clean:
	rm lib/dep.ml
	rm -rf _build
	dune clean