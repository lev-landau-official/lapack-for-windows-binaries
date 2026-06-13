
# LAPACK for Windows binaries

This repository provides pre-compiled static libraries of LAPACK for Windows.
Built with *Intel Parallel Studio XE 2020 (v2020.0.4)* and *Visual Studio 2019 (v16.7.2)*.
Libraries include both standard 32-bit integer (LP64) and 64-bit integer (ILP64) 
variants merged into a single library. ILP64 routines are accessible with the `_64` 
suffix (e.g. `DGEMM_64` instead of `DGEMM`).

## Available Binaries

| Library | Version | Compiler | Architecture | Runtime |
|---------|---------|----------|--------------|---------|
| LAPACK | 3.12.1 | ifort 19.1.3 | x86 | MT |
| LAPACK | 3.12.1 | ifort 19.1.3 | x86 | MTd |
| LAPACK | 3.12.1 | ifort 19.1.3 | x64 | MT |
| LAPACK | 3.12.1 | ifort 19.1.3 | x64 | MTd |
| BLAS | 3.12.1 | ifort 19.1.3 | x86 | MT |
| BLAS | 3.12.1 | ifort 19.1.3 | x86 | MTd |
| BLAS | 3.12.1 | ifort 19.1.3 | x64 | MT |
| BLAS | 3.12.1 | ifort 19.1.3 | x64 | MTd |

## Future Builds

May provide additional configurations (such as MD/MDd or GCC-gfortran etc.) if there's demand for it.
