# XDB
This repository contains the research prototype for the XDB project and the following publications:

- "[Benchmarking for Observability: The Case of Diagnosing Storage Failures](https://www.sciencedirect.com/science/article/pii/S2772485921000065)", Duo Zhang, Mai Zheng, BenchCouncil Transactions on Benchmarks, Standards and Evaluations (TBench), 2021

- "[On Failure Diagnosis of the Storage Stack](https://arxiv.org/abs/2005.02547)", Duo Zhang, Om Rameshwar Gatla, Runzhou Han, Mai Zheng

- "[Position: On Failure Diagnosis of the Storage Stack](https://www.ece.iastate.edu/~mai/docs/papers/2020_HotStorage_PositionPoster.pdf)", Duo Zhang, Om Rameshwar Gatla, Runzhou Han, Mai Zheng, HotStorage, 2020


XDB is an extension of QEMU to capture SCSI and NVME commands. You can activate the functions through QEMU monitor, which is similar to dump instructions in QEMU. 


## Building

QEMU is multi-platform software intended to be buildable on all modern
Linux platforms, OS-X, Win32 (via the Mingw64 toolchain) and a variety
of other UNIX targets. The simple steps to build QEMU are:


.. code-block:: shell

  mkdir build
  cd build
  ../configure
  make



