# Bachelor Thesis

## Python-Bindings for the DASH C++ Template Library

In research areas such as scientific computing and machine learning, Python has established itself as a quasi-standard as a programming language and open source ecosystem over the last decade. Python is based on an interpreter runtime environment, but has been designed from the outset as a domain-specific work environment for statistical calculations and data visualization, and emphasis is placed on simple and robust extensibility through C ++ modules. In order to integrate native compiled, performance-optimized libraries such as LAPACK in Python, until only a few years ago the only way to encapsulate it with C-bindings was to provide it as a module for the Python Runtime API. The rigid and restrictive C API made it difficult to map the full range of functions of an existing library, and in the case of C ++ implementations, such as the DASH Template Library, usually impossible.

From the Python developer community, various solutions and tools have been developed to facilitate the development of native libraries as Python extensions. In addition to the described programmatic problems, conceptual differences are a challenge for mapping C ++ semantics to the slightly typed, interpreted Python environment.

In this thesis the use of a container of the DASH C ++ Template Library for Python extensions is to be investigated.


The implementation of the DASH Bindings are hosted in the official DASH Project source distribution [PyDash](https://github.com/dash-project/pydash)
