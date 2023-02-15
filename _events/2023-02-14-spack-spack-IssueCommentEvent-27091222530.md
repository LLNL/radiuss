---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/33492707?"
user: G-Ragghianti
date: 2023-02-14
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/35423
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/G-Ragghianti' target='_blank'>G-Ragghianti</a> commented on issue <a href='https://github.com/spack/spack/issues/35423' target='_blank'>spack/spack#35423</a>.

<small>I've narrowed down the problem to the try_compile() function in BLASFinder.cmake.  This is trying to link hello.cc to test the BLAS library but is not calling the compiler with "-lmpi" which is required by one of the BLAS_LIBRARIES that is included by the intel-oneapi-mkl package. I was expecting spack's compiler wrapper to add the appropriate linker flags since it knows that mpi is a dependency of intel-oneapi-mkl+cluster.  Any idea why spack is not doing this?...</small>

<a href='https://github.com/spack/spack/issues/35423' target='_blank'>View Comment</a>