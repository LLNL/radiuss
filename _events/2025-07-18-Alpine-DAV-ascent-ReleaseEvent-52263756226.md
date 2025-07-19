---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2025-07-18
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/releases/tag/v0.9.4
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> released <a href='https://github.com/Alpine-DAV/ascent/releases/tag/v0.9.4' target='_blank'>v0.9.4</a>.

<small># 0.9.4 Release Highlights

(adapted from Ascent's [Changelog](https://github.com/Alpine-DAV/ascent/blob/develop/CHANGELOG.md) )

Released 2025-07-18

### Preferred dependency versions for ascent@develop
- cmake@3.23 or newer
- conduit@0.9.4
- vtk-m@2.3.0
- raja@v2025.03.1
- umpire@v2025.03.0
- camp@v2025.03.0
- kokkos@4.4.01
- mfem@4.8

### Added
- Added ability to specify either fields (list of strings) or field (string) for uniform grid sample filter
- Added a `sample` filter that allows you to sample field values at a list of explicit points or along a line.
- Added use case to vtkh data adaptor for blueprint meshes with explicit mesh coordinates with implicit topology (a blueprint structured mesh).
- Added a compressed color table format.
- Added action options relating to logging functionality including `open_log`, `flush_log`, and `close_log` to toggle logging as well as `set_log_threshold` and `set_echo_threshold` to control logging and standard output levels.
- Added a new unified logging infrastructure.
- Added support for unstructured topologies with mixed elements types (for example, hexs and tets).
- Added support for `pyramid` and `wedge` elements.
- Added `sphere`, `cylinder`, `box`, and `plane` options to the slice filter.
- Added a `topologies` option to the relay extract. This allows you to select which topologies are saved. This option can be used with the existing `fields` option, the result is the union of the selected topologies and fields.
- Added `near_plane` and `far_plane` to the camera details provided in Ascent::info()
- Added `add_mpi_ranks` and `add_domain_ids` filters for adding rank and domain fields to a mesh
- Added `transform` filter, which allows you to rotate, scale, reflect, translate, mesh coordinates
- Added python script in src/utilities/visit_session_converters to convert VisIt color table to Ascent actions color table
- Added `fields` option to the project 2d to support scalar rendering of specific fields.
- Added `dataset_bounds` option to the project 2d, which can be used instead of a full 3D camera specification
- Added support for triggers to execute actions from multiple files via an `actions_files` option that takes a list of actions files.
- Added an `external_surfaces` transform filter, that can be used to reduce memory requirements in pipelines where you plan to only process the external faces of a data set.
- Added a `declare_fields` action, that allows users to explicitly list the fields to return for field filtering. This option avoids complex field parsing logic.
- Added a 2d camera mode (`camera/2d: [left, right, bottom, top]`) to scene render cameras and the `project_2d` (scalar rendering) filter cameras.
- Added support for `include` keyword to include children from yaml files in an input node trees
- Added support for special keyword formatting for output paths. Current supported keywords include
`cycle`, `family`, and `time`.
- Added support for formatting of output paths for extracts.
- Added support for parallel timestep mode to replay allowing for parallel in time processes in addition to pre-existing distributed-memory parallelism.

### Changed
- Extensive improvements to Rover X Ray Ray Tracing Diagnostic features (the `xray` extract).
- Changed the replay utility's binary names such that `replay_ser` is now `ascent_replay` and `raplay_mpi` is now `ascent_replay_mpi`. This will help prevent potential name collisions with other tools that also have replay utilities.
- Updated several preferred tpl versions
- Changed bounding box used for default scene bounds to be the union of all topologies used in scene plots. Perviously, the union of all topologies in the dataset where used. 

### Fixed
- Fixed WarpX filter that was not allowing for rendering of the output streamlines
- Fixed Uniform Grid bug only accepting 2D slices along the Z-axis.
- Resolved a few cases where MPI_COMM_WORLD was used instead instead of the selected MPI communicator.
- Resolved a bug where a sharing a coordset between multiple polytopal topologies would corrupt mesh processing.
- Fixed a bug with Cinema resource output that could lead to corrupted html results.
- Fixed a bug where controls for world and screen annotations where ignored in Cinema renders.
- Fixed a bug in Uniform Grid Sampling and changed how ties for valid points are broken.

## Docker Containers
 - **alpinedav/ascent:0.9.4**
 - **alpinedav/ascent-jupyter:0.9.4**



## Summary of Pull Requests

* update relnotes helper script by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1301
* add support for all wedge and all pyramid topos by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1302
* Add ascent_opts["default_dir"] to "image_name" images by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1295
* add topology selection relay extract option by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1300
* main docker container updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1305
* add near and far plane to camera info and a few code formatting changes by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1299
* misc cleanup for replay by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1308
* mpi world comm audit and fixes by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1307
* fix wrong mpi define undermining replay by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1315
* another fix for replay mpi by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1316
* Uniform Grid Missing Topology Bug by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1319
* fix typo in backend doc by @mlohry in https://github.com/Alpine-DAV/ascent/pull/1320
* Remove volatile from RAJA atomics wrappers by @MrBurmark in https://github.com/Alpine-DAV/ascent/pull/1325
* bugfix for typo in dray stats, provided by stephdempsey by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1327
* bugfix for vtk-m ray culling issue by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1324
* Fixed mpi communication from MPI_COMM_WORLD to the one defined in ascent by @mvictoras in https://github.com/Alpine-DAV/ascent/pull/1330
* add support for mixed element unstructured meshes   by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1309
* rtd config: add jquery to req extensions by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1334
* generate_sides multi topo shared coordset fix by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1333
* install cmds for laghos helpers and script updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1336
* VTK-m MIR by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1326
* auto slice bug by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1338
* tutorial docs updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1339
* add case testing py venv support by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1343
* update tutorial docs link to latest, add patch info to changelog by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1346
* add silo build support to build_ascent by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1342
* wip: build ascent docker example by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1347
* Add terminal-based steering interface via an extract by @siramok in https://github.com/Alpine-DAV/ascent/pull/1345
* add siramok terminal steering example  by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1351
* docker tutorial updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1352
* build_ascent caliper support by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1344
* Task/2024 07 camfrust meshes by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1354
* build_ascent caliper + hip support by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1359
* update tutorial slides link by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1363
* updates to rzadams and rzvernal for mpi by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1362
* adds mpi ranks fields by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1349
* Replay parse actions before loading data by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1366
* Task/2024 08 renaming replay ser and replay mpi by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1372
* Relay Extract: Silo/Overlink by @JustinPrivitera in https://github.com/Alpine-DAV/ascent/pull/1377
* add data on device test and example by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1370
* fix for replay mpi case (fix defs) by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1383
* add device conversion for uint64 by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1373
* frontier build updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1381
* add new slice implicit fun cases, sphere, cyln, box, and plane by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1395
* Fix for saving metadata bug on cscs alps by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1402
* add ascent transform filter by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1403
* Empty pipeline error when no filter by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1409
* Fixing Nan errors in Camera Frustum Mesh by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1397
* rzhound build script and replay error change by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1414
* cinema fixes by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1425
* fix for htg param parsing by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1419
* coord_type typo by @mvictoras in https://github.com/Alpine-DAV/ascent/pull/1408
* add rocm 6.3 container for ci by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1429
* aurora bv scripts by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1427
* unified logging infrastructure by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1426
* Fixed ascent clone path by @mvictoras in https://github.com/Alpine-DAV/ascent/pull/1434
* add to tutorials and pubs list by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1443
* Update Pipelines.rst by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1444
* small fixes by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1447
* Add conversion for VisIt color table to Ascent actions color table by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1446
* Fix broken link and add resource to Utilities.rst by @cyr1l0u in https://github.com/Alpine-DAV/ascent/pull/1439
* add domains change to zonal by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1453
* Update Partition filter & docs by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1412
* scalar renderer (project 2d) add option to select fields by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1454
* dataset_bounds support for project_2d by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1456
* Adding actions for opening, flushing, and closing the logs by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1442
* Enabling binning of point clouds (grid-less data) by @jfavre in https://github.com/Alpine-DAV/ascent/pull/1459
* uniform grid fixes by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1461
* build_ascent zfp support by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1460
* Fix issues with umpire in ascent_config.mk.in and dray_config.mk.in. by @brugger1 in https://github.com/Alpine-DAV/ascent/pull/1463
* Compact color table args by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1457
* Conduit::Blueprint Bent Grid Example Case by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1466
* add external_surfaces filter by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1471
* add ascent lib version details to info by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1472
* add support for actions_files (list of actions files) to triggers by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1469
* add reflect support to the transform filter by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1473
* add save_info docs by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1474
* refactor raja device guards by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1475
* warnings pass done on macOS w/ clang by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1478
* add declare fields action and docs updates by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1483
* add 2d camera mode controls for rendering and project_2d by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1484
* declare fields logic fix by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1488
* Include Yaml by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1482
* Task/2025 3 18 1413 camera zoom of 0 causes hang by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1487
* fix to resource compiler and update resource headers by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1492
* Add device copy for uints & ints by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1495
* update to vtkm 2.2 by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1445
* Fix uniform grid to account 2D slices along all axis by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1499
* build_ascent: update conduit and mfem by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1505
* resolve a compilation error of VTK-m with CUDA 12.6 by @jfavre in https://github.com/Alpine-DAV/ascent/pull/1507
* build_ascent: update blt, raja, camp, and umpire  by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1485
* Task/2025 3 27 1428 path enhancements rollup issue fmt path strings by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1496
* Non existant directory check by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1497
* Fix conflicting family value found in output test file names by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1511
* guard against rocm detail namespace agression by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1520
* uberenv tpl updates, vtk-m 2.3 update by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1509
* update min cmake version to 3.23 by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1523
* relax tolerance for render 3d implicit pts by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1525
* Task/5 19 2025 1519 docs issues by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1528
* Adding documentation that queries will not create a named output that can be referenced elsewhere by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1530
* fix rocm 6.4 build by @tomstitt in https://github.com/Alpine-DAV/ascent/pull/1531
* X Ray Filter First Enhancements by @siramok in https://github.com/Alpine-DAV/ascent/pull/1529
* relay blueprint -- add generated root file as path in extract info by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1480
* Initial work for getting basic blueprint mesh output parity between rover and visit by @siramok in https://github.com/Alpine-DAV/ascent/pull/1535
* add test for external surfaces result feed into multiple pipelines by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1537
* Refactor XRay initialization + camera params (re PR) by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1543
* Remove Rover's volume renderer by @siramok in https://github.com/Alpine-DAV/ascent/pull/1544
* Replace Rover's setting structs with conduit nodes by @siramok in https://github.com/Alpine-DAV/ascent/pull/1545
* Change rover's default background intensity to 0.0f by @siramok in https://github.com/Alpine-DAV/ascent/pull/1548
* Use a global settings node for rover by @siramok in https://github.com/Alpine-DAV/ascent/pull/1549
* Rover width, height cleanup + adds settings used to the output by @siramok in https://github.com/Alpine-DAV/ascent/pull/1551
* Simplify Rover's engine code by @siramok in https://github.com/Alpine-DAV/ascent/pull/1553
* Update Uniform Sample to accept and output multiple fields by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1527
* DRAFT: Task/7 5 2025 fmt string followup by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1524
* Simplify Rover's scheduler code by @siramok in https://github.com/Alpine-DAV/ascent/pull/1554
* Add spatial topology blueprint mesh to Rover's output by @siramok in https://github.com/Alpine-DAV/ascent/pull/1556
* add vtkm patch for z extents ray culling bug by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1561
* Bug: Fmt string family value directory check for no-format strings by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1562
* performance annotations by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1550
* updates for building on macos 15.5 (seq) by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1570
* warpx unit test by @nicolemarsaglia in https://github.com/Alpine-DAV/ascent/pull/1489
* update windows gact runner, since windows 2019 will be unsupported soon by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1552
* Fix rover's optical depth output by @siramok in https://github.com/Alpine-DAV/ascent/pull/1569
* Task/6 26 25 1536 conduit error when rendering a rectilinear mesh with integer coordinate values by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1568
* Move verbiage in LICENSE around and update it to conform with GitHub format by @markcmiller86 in https://github.com/Alpine-DAV/ascent/pull/1574
* add a sample filter that samples at points (list or specd by line) by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1571
* Task/2025 4 15 1275 replay parallel multi timestep mode by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1502
* update uberenv and spack pkgs by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1575
* Resolve many Rover TODOs by @siramok in https://github.com/Alpine-DAV/ascent/pull/1573
* Add compositing for Rover's optical depth output by @siramok in https://github.com/Alpine-DAV/ascent/pull/1578
* Tast/6 19 25 1510 update tutorials to use new fmt path strings by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1576
* per scene default bounds using only relevent topos by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1579
* Remove Rover tests box clip workaround by @siramok in https://github.com/Alpine-DAV/ascent/pull/1581
* Correcting URL to docs in jupyter notebook by @emily-howell in https://github.com/Alpine-DAV/ascent/pull/1583
* 0.9.4 release prep by @cyrush in https://github.com/Alpine-DAV/ascent/pull/1577

## New Contributors
* @mlohry made their first contribution in https://github.com/Alpine-DAV/ascent/pull/1320
* @MrBurmark made their first contribution in https://github.com/Alpine-DAV/ascent/pull/1325
* @cyr1l0u made their first contribution in https://github.com/Alpine-DAV/ascent/pull/1439
* @markcmiller86 made their first contribution in https://github.com/Alpine-DAV/ascent/pull/1574

**Full Comparsion**: https://github.com/Alpine-DAV/ascent/compare/v0.9.3...v0.9.4</small><a href='https://github.com/Alpine-DAV/ascent/releases/tag/v0.9.4' target='_blank'>View Comment</a>