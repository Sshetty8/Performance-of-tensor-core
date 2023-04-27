# Performance-of-tensor-core
This program cannot be run independently. Please download the git repository by Nvidia, provided in the following link and follow the instructions below: https://github.com/NVIDIA/cuda-samples
 * Navigigate through the folders as mentioned below to reach the destined program.
  cuda-samples -> Samples -> 3_CUDA_Features -> cudaTensorCoreGemm
 * Once you reach the folder 'cudaTensorCoreGemm', replace the contents of the file cudaTensorCoreGemm.cu with the contents of the file in cudaTensorCorePerformance.cu (found in this repository).

The program records the number of clock cycles used to perform the multiplication of each element in the program. This is acheieved through an array, which is of the same size as the resultant matrix.

The program also records the number of clock cycles used to perform the entire matrix multiplication.
