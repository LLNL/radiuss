---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/45609916?"
user: gunney1
date: 2025-04-03
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/releases/tag/v0.11.0
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/gunney1' target='_blank'>gunney1</a> released <a href='https://github.com/LLNL/axom/releases/tag/v0.11.0' target='_blank'>v0.11.0</a>.

<small>###  Added
- Added a new "Mir" Axom component for accelerated Material Interface Reconstruction (MIR) algorithms.
  MIR algorithms take Blueprint meshes with a matset and they use the matset's material information
  to split any input zones that contain multiple materials into zones that contain a single material.
  The Mir component provides an implementation of the Equi-Z MIR algorithm, which is a visualization-
  oriented algorithm that produces smooth interfaces between zones and their neighbors. The Mir
  component also provides a 2D ELVIRA algorithm, which reconstructs polygonal shapes and preserves
  volume fractions.
- Support in `quest::IntersectionShaper` for Blueprint mesh stored in a `conduit::Node`
  or `sidre::Group`.
- Adds new CMake configuration options, `AXOM_ENABLE_ASAN` and `AXOM_ENABLE_UBSAN`, to enable/disable AddressSanitizer and UndefinedBehaviorSanitizer respectively in Axom. Default is OFF for both.
- A number of new `klee::Geometry` constructors are added, for the different shapes now supported.
  This is a temporary change.  The class will be subclassed in the future to support a diversity of geometries.
- Support some analytical shapes in `IntersectionShaper`.
- Support generating shapes in memory (not requiring input files).
- `sidre::View` holding array data may now be re-shaped.  See `sidre::View::reshapeArray`.
- Sina C++ library is now a component of Axom
- Adds optional dependency on [Open Cascade](https://dev.opencascade.org). The initial intention is 
to use Open Cascade's file I/O capabilities in support of Quest applications.
- Adds `primal::NURBSCurve` and `primal::NURBSPatch` classes, supported by `primal::KnotVector`.
- Adds a Quest example that reads in a STEP file using Open Cascade and processes its geometry
- Adds a piecewise method to load external data using `sidre::IOManager`.  This adds new overloaded methods
  of `loadExternalData` in `sidre::IOManager` and `sidre::Group`.
- Adds intersection routines between `primal::Ray` objects and `primal::NURBSCurve`/`primal::NURBSPatch` objects.
- Adds LineFileTagCombiner to Lumberjack to allow combining messages if line number, file, and tag are equal.
- Adds some support for 2D shaping in `quest::IntersectionShaper`, using STL meshes with zero for z-coordinates or in-memory triangles as input.
- Adds ability in Lumberjack to own and set communicators.
- Adds `NonCollectiveRootCommunicator` to Lumberjack to provide an MPI-based communicator for logging messages non-collectively.

###  Changed
- Updates blt submodule to [BLT version 0.7.0][https://github.com/LLNL/blt/releases/tag/v0.7.0]
- Updates to [MFEM version 4.7.0][https://github.com/mfem/mfem/releases/tag/v4.7]
- Updates to [Caliper version 2.12.1][https://github.com/LLNL/Caliper/releases/tag/v2.12.1]
- Updates to [Conduit version 0.9.3][https://github.com/LLNL/conduit/releases/tag/v0.9.3]
- Updates to [RAJA version 2025.03.0][https://github.com/LLNL/RAJA/releases/tag/v2025.03.0]
- Updates to [camp version 2025.03.0][https://github.com/LLNL/camp/releases/tag/v2025.03.0]
- Updates to [Umpire version 2025.03.0][https://github.com/LLNL/Umpire/releases/tag/v2025.03.0]
- `primal::NumericArray` has been moved to `core`.  The header is `core/NumericArray.hpp`.
- `quest::Shaper` and `quest::IntersectionShaper` constructors require a runtime policy.
  Changing the policy after construction is no longer supported.
- Importing Conduit array data into `sidre::View` now allocates destination
  data using the `View`'s parent's allocator ID, instead of always using
  host memory.  This is consistent with the behavior of deep-copying data
  from Sidre.
- ItemCollection and its child classes MapCollection, ListCollection, and IndexedCollection were moved from Sidre
  to core.  The namespace prefix for these classes is now `axom::` instead of `axom::sidre`.  The internal usage of
  these types within Sidre Datastore and Group is unchanged.
- `MFEMSidreDataCollection::LoadExternalData` now takes two optional string parameters, one that is a
  filename (defaults to the `name` member variable) and the other is a `Group` path relative to the base of
  the Data Collection itself (defaults to the root of the `DataStore`).
- `SLIC_ASSERT`,`SLIC_ASSERT_MSG`,`SLIC_CHECK`, and `SLIC_CHECK_MSG` macros delegate to assert() within HIP device kernels.

###  Fixed
- Fixes compilation issue with RAJA@2024.07 on 32-bit Windows configurations. 
  This required a [RAJA fix to avoid 64-bit intrinsics](https://github.com/LLNL/RAJA/pull/1746), 
  as well as support for 32-bit `Word`s in Slam's `BitSet` class.
- Minor bugfix to `primal::intersect(segment, ray)` to better handle cases when segment and ray overlap.
- Fixes a memory leak in `axom::Array` copy constructor.
</small><a href='https://github.com/LLNL/axom/releases/tag/v0.11.0' target='_blank'>View Comment</a>