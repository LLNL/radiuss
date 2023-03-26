---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/6210171?"
user: bvanessen
date: 2023-03-25
repo_name: LLNL/lbann
html_url: https://github.com/LLNL/lbann/releases/tag/v0.103
repo_url: https://github.com/LLNL/lbann
---

<a href='https://github.com/bvanessen' target='_blank'>bvanessen</a> released <a href='https://github.com/LLNL/lbann/releases/tag/v0.103' target='_blank'>v0.103</a>.

<small>============================== Release Notes: v0.103 ==============================

C++ API:
 - Added ability to load models and run inference from external C++ applications
 - Added inference-only execution algorithm

Support for new training algorithms:
 - 2nd-order optimization with K-FAC.
   Currently supports fully-connected, convolution, and GRU layers.
 - Added Sub-graph parallelism support for multi-branch architectures
   (split, slice, sum, and concat layers)
 - Data + sub-graph parallelism for in-core models (D&SP and D&SP-cSub)
 - Initial sub-graph parallelism support for common layers in
   Transformers
 - Model topology mutation in LTFB/PBT
 - Added sub-grid parallelism support for K-FAC using primary and
   secondary grids
 - Truncation selection exchange for LTFB/PBT
 - Regularized evolution for LTFB/PBT
 - Hyperparameter grid search
 - Multi-GAN training algorithm with multiple discriminators

Support for new network structures:
 - Edge-conditioned graph neural networks
 - RoBERTa with pretrained weights

Support for new layers:
 - Added support for 2D Matrices for Scatter and Gather layers
 - Added support for distributed Scatter and Gather layers
 - DistConv enabled 3D MatMul
 - Added image rotation layer and composite image transformation layer
   (rotate, shear, translate)
 - Added distributed tensor parallelism with channelwise decomposition for channelwise fully connected layer
 - Added "binary-with-constant" operators
 - Updated deconvolution layer to match PyTorch's API
 - Updated identity layer to copy tensors to enable tensor parallelism in subsequent layers in the compute graph
 - Added IdentityZero layer that allows alternating generator/discriminator
   updates for training GANs.
 - Added an External layer that enables separately-compiled library to be loaded dynamically
 - Added support for labels_only mode on data-parallel cross entropy layer

Python front-end:
 - Added support for building and launching jobs on Fugaku
 - Added Riken as a known compute center
 - Added Perlmutter as a known compute center
 - Added support for PJM as job launcher
 - Unified convolution/deconvolution interface to better approximate PyTorch.
 - Added circular (periodic) padding transformation for 2D and 3D tensors
 - Added support for Flux job scheduler

Performance optimizations:
 - Enabled the input layers to use a view of the I/O buffers in the
   buffered data coordinator
 - Use default-allocated GPU memory for long-lived buffers
 - Optimized GPU kernels for entry-wise operators
 - Optionally use default-allocated GPU memory for long-lived buffers

Model portability & usability:
 - Weight initialization from NumPy files
 - Expanded layer documentation

Experiments & Applications:
 - Example for training Transformer model with D&SP and D&SP-cSub
 - PROBIESNet model for HRRL data
 - Cosmo 3D GAN
 - MNIST GAN
 - Image GAN
 - Example Distributed Graph Convolutions Networks
 - NASNet
 - RoBERTa

Internal features:
 - Added operator class
 - Added AlternateUpdates callback to be used with IdentityZero layers for
   training GANs.
 - Added support for serializing network architectures to protobuf format.
 - Reformatted headers and implementation files for a more IWYU paradigm.
 - General support for ROCm-enabled DistConv
 - Support fo use of libfabric plugin for RCCL and NCCL
 - Framework-wide improvements in support for ROCm and MIOpen
 - Callback for alternating optimizer layer update
 - Command line argument to hang the LBANN application for debuggin
 - Add a cuTT/hipTT backend to the permute layer
 - Add a permute layer utilizing cuTENSOR for the permute implementation
 - Weight initializer from NumPy file

I/O & data readers:
 - Updated SMILES data reader to use sample lists
 - Added explicitly managed buffered reading and local unpacking for the
   SMILES data reader to minimize file access
 - Sample lists with integral indices can use range format (start ... end)
 - Added a new extensible HDF5 data reader that uses a data set schema
   and experiment schema files to define how the data is represented.
   This allows the user to change the representation of data without
   changing the data reader.
 - Changed the input layer to take a data field and only produce a
   single output.  Currently valid Data fields are samples, labels,
   and responses.
 - Added support for using arbitrary field names with HDF5 data reader.
 - Updated the data coordinator and data readers to
   take dynamic data fields rather than fixed fields.  Input buffers
   are no long allocated for fields that are not used in active
   models.
 - Added support in the generic data reader and synthetic data reader
   clases for arbitrary data fields.
 - Added support for data readers to return full Conduit nodes to the
   Data Coordinator.
 - Data coordinator can now directly return packed data fields to
   input layers.
 - Added padding and cutout transformations

Build system:
 - Added support for using uptream Spack repositories
 - Added support to reuse existing Spack environments, which
   significantly decreases the startup time of running a CI job
 - Enforce consistent GPU targets in Spack environment
 - Switched from Bamboo to GitLab CI framework

Bug fixes:
 - Fixed GPU kernels that launched with more blocks than allowed
 - Fixed build and runtime errors with DistConv
 - Use correct LayerNorm operaton in "Attention Is All You Need"
   Transformer
 - Fixed a bug where the input layer performed unnecessary memory
   allocations.
 - Bug fixes within Cosmoflow and U-Net models
 - Fixed a bug in the GPU-based computation of the batchnorm
 statistics
 - Patch for when distconv'd input layer is followed by non-distconv layer
 - Bugfix input layer activations: Fixed the input layer so that it
   would only resize the activation matrix if it wasn't already setup
   to be a view of the data_coordinator's matrix.  This addresses a
   signficant performance bug in the data ingestion where the
   activation matrix was a view into the data coordinator's internal buffers.
 - Fixed bad convolution parameters producing incorrect layer shapes.
 - Enabling tensor copy on distconv-enabled Identity layer
 - General cleanup and improvement in the coverage and robustness of
   CI testing
 - Fix buffer overflow in SMILES data reader
 - Fix a bug in TSE
 - Do not construct bias weights when not needed in conv and FC modules
 - Use tournament set in LTFB with truncation selection exchange
 - Cleanup data reader tests memory leaks
 - Fixed a buffer overrun, heap overflow, and double allocation of the
   data store in the SMILES data reader
 - Match LayerNorm and InstanceNorm layers to PyTorch
 - Make sure GPU grid dims are valid in slice/concat layers
 - Fixed incorrect matrix ording in K-FAC for conv layer
 - Bugfix for polynomial learning rate schedule</small><a href='https://github.com/LLNL/lbann/releases/tag/v0.103' target='_blank'>View Comment</a>