# Awesome Python Implementations

## Mainstream implementations

- [CPython](https://github.com/python/cpython) ★53615 - The reference implementation of Python, written in C.
- [PyPy](https://foss.heptapod.net/pypy/pypy) - Python in Python, includes a tracing JIT compiler.
- [RustPython](https://github.com/RustPython/RustPython) ★15056 - Python interpreter written in Rust.
- [IronPython](https://github.com/IronLanguages/ironpython3) ★2135 - Python in C# for the Common Language Runtime (CLR/.NET).
- [GraalPython](https://github.com/oracle/graalpython) ★980 - Python in Java, using the Graal just-in-time compiler and the Truffle interpreter implementation framework
- [Jython](https://github.com/jython/jython) ★867 - Python in Java for the Java platform.

## Lightweight implementations

Mainly for embedded systems.

- [Micropython](https://github.com/micropython/micropython) ★16660 - MicroPython - a lean and efficient Python implementation for microcontrollers and constrained systems
- [CircuitPython](https://github.com/adafruit/circuitpython) ★3549 - CircuitPython - a Python implementation for teaching coding with microcontrollers - Fork of MicroPython by Adafruit.

### Dead projects

- [Pymite](https://github.com/giuseppebarba/pymite) ★4 - Python-on-a-Chip (p14p) is a project to develop a reduced Python virtual machine (codenamed PyMite) that runs a significant subset of the Python 2.6 language on microcontrollers without an OS.

## Python to JavaScript transpilers

### Active projects

- [Brython](https://github.com/brython-dev/brython) ★6027 - a way to run Python in the browser through translation to JS
- [PScript](https://github.com/flexxui/pscript) ★240 -  Python to JavaScript compiler
- [Transcrypt](http://www.transcrypt.org/) - Python 3.6 to JS precompiler with lean and fast generated code, sourcemaps, built-in minification, optional static type-checking, JSX support

### Dead projects

- [pyjs](https://github.com/pyjs/pyjs) ★1122 - (formerly Pyjamas) a Python to JS compiler plus Web/GUI framework
- [Pyjaco](https://github.com/chrivers/pyjaco) ★141 - Similar to Pyjs but more lightweight


## Compilers

These compilers usually implement something close to Python, although some compilers may impose restrictions that alter the nature of the language:

- [Numba](https://github.com/numba/numba) ★8640 - NumPy aware dynamic Python compiler using LLVM

- [Nuitka](https://github.com/Nuitka/Nuitka) ★8840 - a Python-to-C++ compiler using libpython at runtime, attempting some compile-time and run-time optimisations. Interacts with CPython runtime.

- [Cython](https://github.com/cython/cython) ★7966 - a widely used optimising Python-to-C compiler, CPython extension module generator, and wrapper language for binding external libraries. Interacts with CPython runtime and supports embedding CPython in stand-alone binaries.

- [Pythran](https://github.com/serge-sans-paille/pythran) ★1895 - Pythran is an ahead of time compiler for a subset of the Python language, with a focus on scientific computing. It takes a Python module annotated with a few interface descriptions and turns it into a native Python module with the same interface, but (hopefully) faster.

- [MyPyC](https://github.com/mypyc/mypyc) ★1486 compiles fully typed Python code to a C extension, based on mypy. (Source code [here](https://github.com/python/mypy/tree/master/mypyc))
