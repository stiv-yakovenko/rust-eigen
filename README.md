# Eigen number calculation in Rust

This piece of code is transpiled EigenvalueDecomposition.java from Jama framework.
I had to do this, because I haven't found any buildable rust opensource project
to calculate real eigen values. There are many packages which are usually bound to
openBLAS, but I can't build them with gnu toolchain, and that's the only toolchain, which
allows gdb (and thus IDE) debug nowadays.

Quality code is far from perfect, hopefully someone will appreciate my one day of
manual code conversion nightmare and mention me in the source code.

Stepan Yakovenko
