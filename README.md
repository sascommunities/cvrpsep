# CVRPSEP

## Overview

This repository is a fork of the original CVRPSEP package hosted at [Jens Lysgaard's site](https://sites.google.com/view/jens-lysgaard/cvrpsep). The initial commit is a copy of the original source. Subsequent commits will include contributed fixes and improvements.

This library is described by the original author as follows:

>The CVRPSEP package is a collection of routines, written in the C programming language, for separation of various classes of cuts in branch-and-cut algorithms for the Capacitated Vehicle Routing Problem. The routines are those that were used in the reference given below. The package contains separation routines for rounded capacity inequalities, homogeneous multistar inequalities, generalized multistar inequalities, framed capacity inequalities, strengthened comb inequalities, and hypotour inequalities. In addition, the package contains a routine for generating candidate sets for branching.

## Installation

Clone the repository and build the static library:

```sh
git clone <repository-url>
cd cvrpsep
make
```

This produces the static library `obj/libcvrpsep.a`. Link `obj/libcvrpsep.a` into your own program and include the relevant headers from `h/`.

## Contributing

Maintainers are accepting patches and contributions to this project.

## License

This project is licensed under the [Common Public License 1.0](LICENSE).

## Third-Party Dependencies

This project has no third-party runtime dependencies. Building it requires only a C++ compiler and GNU `make`.

## Additional Resources

* [Original CVRPSEP package (Jens Lysgaard)](https://sites.google.com/view/jens-lysgaard/cvrpsep)
* J. Lysgaard, A. N. Letchford, R. W. Eglese, "A new branch-and-cut algorithm for the capacitated vehicle routing problem," *Mathematical Programming*, 100(2), 423–445, 2004.

