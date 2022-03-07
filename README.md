# Hpmoon

Hpmoon is a parallel and distributed multi-objective genetic algorithm to EEG classification. The evolutionary procedure corresponds to an island-based model whose subpopulations are distributed among the nodes of a cluster. The application is able to parallelize the evaluation of the individuals using all the CPU-GPU devices simultaneously, which provides up to 4 levels of parallelism.

## Requirements

Hpmoon requires a GCC compiler and OpenCL 1.2 compliant CPU-GPU devices. It also depends on the following APIs and libraries:

* [OpenMPI](https://www.open-mpi.org/doc/current/).
* [AMD APP SDK v2.9.1](http://developer.amd.com/wordpress/media/2012/10/AMD_APP_SDK_Release_Notes_Developer2.pdf) or later.
* [Doxygen](https://www.doxygen.nl/index.html) if you want to generate documentation.

## Documentation

Hpmoon is fully documented in its [Github Pages](https://efficomp.github.io/Hpmoon/). In addition, the `Makefile` file contains a rule to generate [Doxygen](https://www.doxygen.nl/index.html) documentation in the `docs/html` folder.

## Usage

The `docs` folder contains the file `user_guide.pdf` with the instructions necessary to use the program. You can also display help by running the program with the `-h` option.

## Acknowledgments

This work has been funded by:

* Spanish *Ministerio de Economía y Competitividad* under grants number TIN2012-32039 and TIN2015-67020-P.
* Spanish [*Ministerio de Ciencia, Innovación y Universidades*](https://www.ciencia.gob.es/) under grant number PGC2018-098813-B-C31.
* [*European Regional Development Fund (ERDF)*](https://ec.europa.eu/regional_policy/en/funding/erdf/).

<div style="text-align: right">
  <img src="https://raw.githubusercontent.com/efficomp/Hpmoon/main/docs/logos/mineco.png" height="70">
  <a href="https://www.ciencia.gob.es/">
    <img src="https://raw.githubusercontent.com/efficomp/Hpmoon/main/docs/logos/miciu.jpg" height="70">
  </a>
  <a href="https://ec.europa.eu/regional_policy/en/funding/erdf/">
    <img src="https://raw.githubusercontent.com/efficomp/Hpmoon/main/docs/logos/erdf.png" height="70">
  </a>
</div>

## License

[GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.md).

## Copyright

Hpmoon © 2015 [EFFICOMP](https://efficomp.ugr.es/).

## Publications

1. J. J. Escobar, J. Ortega, A. F. Díaz, J. González, and M. Damas. "Energy-aware Load Balancing of Parallel Evolutionary Algorithms with Heavy Fitness Functions in Heterogeneous CPU-GPU Architectures". In: *Concurrency and Computation: Practice and Experience* 31.6 (2019), e4688. doi: 10.1002/cpe.4688
1. J. J. Escobar, J. Ortega, A. F. Díaz, J. González, and M. Damas. "Time-energy Analysis of Multi-level Parallelism in Heterogeneous Clusters: The Case of EEG Classification in BCI Tasks". In: *The Journal of Supercomputing* 75.7 (2019), pp. 3397-3425. doi: 10.1007/s11227-019-02908-4.
1. J. J. Escobar, J. Ortega, A. F. Díaz, J. González, and M. Damas. "A Power-Performance Perspective to Multiobjective Electroencephalogram Feature Selection on Heterogeneous Parallel Platforms". In: *Journal of Computational Biology* 25.8 (2018), pp. 882-893. doi: 10.1089/cmb.2018.0080.
1. J. J. Escobar, J. Ortega, J. González, M. Damas, and A. F. Díaz. "Parallel High-dimensional Multiobjective Feature Selection for EEG Classification with Dynamic Workload Balancing on CPU-GPU". In: *Cluster Computing* 20.3 (2017), pp. 1881-1897. doi: 10.1007/s10586-017-0980-7.
