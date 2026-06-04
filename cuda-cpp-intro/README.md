# CUDA C++ intro training

This folder documents hands-on exercises completed after the NVIDIA Deep Learning Institute course An Even Easier Introduction to CUDA using CUDA C/C++. 

What this covers:
- CUDA's host/device execution model and the standard workflow for launching GPU work.

- Thread and block indexing using threadIdx, blockIdx, blockDim, and gridDim.

- Why kernel printf() output is not guaranteed to appear in sequential order when many GPU threads execute concurrently.

- How 1D launches differ from 2D/3D launches, and why x, y, and z dimensions exist.