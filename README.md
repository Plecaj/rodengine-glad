# RodEngine Glad Loader

Generated OpenGL loader used by RodEngine.

Generation parameters:

- Generator: glad 0.1.36
- Specification: `gl`
- API: `gl=4.6`
- Profile: `core`
- Loader: enabled
- Extensions: none

Original generator URL:

https://glad.dav1d.de/#profile=core&language=c&specification=gl&loader=on&api=gl%3D4.6

This repository intentionally stores the generated loader output instead of
generating it as part of the normal CMake configure/build step. The loader
configuration changes rarely, while committing the generated files keeps
RodEngine builds simple and reproducible.
