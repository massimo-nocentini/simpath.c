
build:
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath-reduce simpath-reduce.c -lgb
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath simpath.c -lgb
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath-cycles simpath-cycles.c -lgb
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath-ham simpath-ham.c -lgb
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath-ham-any simpath-ham-any.c -lgb
	clang -Wall -O3 -I/usr/local/sgb/include -fPIC -o simpath-directed-cycles simpath-directed-cycles.c -lgb

install:
	install -Dm755 simpath-reduce /usr/local/bin/simpath-reduce