

fetch:
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath.w
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath-reduce.w
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath-example.tgz
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath-cycles.ch
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath-ham.ch
	wget https://www-cs-faculty.stanford.edu/~knuth/programs/simpath-ham-any.ch
	mkdir example && mv simpath-example.tgz example && cd example && tar xf simpath-example.tgz

build:
	cweave simpath.w && tex simpath.tex && dvipdf simpath.dvi
	cweave simpath.w simpath-cycles.ch simpath-cycles.tex && tex simpath-cycles.tex && dvipdf simpath-cycles.dvi
	cweave simpath.w simpath-ham.ch simpath-ham.tex && tex simpath-ham.tex && dvipdf simpath-ham.dvi
	cweave simpath.w simpath-ham-any.ch simpath-ham-any.tex && tex simpath-ham-any.tex && dvipdf simpath-ham-any.dvi
	cweave simpath-reduce.w && tex simpath-reduce.tex && dvipdf simpath-reduce.dvi