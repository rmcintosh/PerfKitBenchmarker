Breaking changes:
-

New features:
- Added CUDA-enabled HPCG benchmark (GH-1395)

Enhancements:
- Added basic auth support for Mesos provider. (GH-1390)
- Added --failed_run_samples_error_length flag to limit failed run error length (GH-1391)
- Added `__eq__` and `__ne__` to IntegerList (GH-1395)
- Added total_free_memory_kb to VirtualMachine class and implemented it for
  Linux vms (GH-1397)
- Created hpc_util for a place to share common HPC functions

Bug fixes and maintenance updates:
- Fix provision phase of memcached_ycsb benchmark for non-managed memcached instances (GH-1384)
