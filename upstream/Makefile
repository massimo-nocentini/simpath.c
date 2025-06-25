

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