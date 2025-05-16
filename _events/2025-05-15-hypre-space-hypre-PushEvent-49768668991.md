---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2025-05-15
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/479c37647c3f051fe225007f6eed230d49112aa1
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>Recmat - Adds support for symmetric matrices in the StructMatmult routine and adds optimizations to PFMG (#1249)

* Adjusts communication for symmetric storage
* Automatically determines if the product matrix in matmult is symmetric
* Computes only the stored symmetric coefficients in matmult (the "lower triangle" so to speak)
* Modifies the PFMG setup to reduce memory copies in the matmult calls
* Cleans up the kernel optimization code in matmult. Using a mask (not a bit mask) simplifies things.
* Makes a better decision about when a mask is needed in matmult.
* Computes a better data space for the matrices involved in the matrix product.
* Tries to avoid unnecessary matrix resizes in matmult. Now, PFMG often does not require a resize-with-copy.
* Adds loop unrolling optimizations to matvec for rectangular matrices (previously only square matrices were unrolled).</small>

<a href='https://github.com/hypre-space/hypre/commit/479c37647c3f051fe225007f6eed230d49112aa1' target='_blank'>View Commit</a>