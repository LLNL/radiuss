---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2025-05-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4853
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4853' target='_blank'>mfem/mfem#4853</a>.

<small>@adam-sim-dev, similar to `GetFaceToAllElementTable()`, the columns of `GetVertexToAllElementTable()` do not need to correspond to global element indices. Instead, the column indices `0,...,NE-1` (`NE` is the local number of elements) are used for the local elements and the indices `NE,...,NE+NNE-1` (with `NNE` being the number of face-neighbor elements) are used for face-neighbor elements. Each rank has its own array of face-neighbor elements and data about those elements (such as their coordinates, element attribute, element type, etc) and it can be accessed using these local indices. In `ParMesh`, this is the `Array<Element*> face_nbr_elements`; vertices of these elements are stored in `Array<Vertex> face_nbr_vertices` (when the mesh does not use the nodes grid function) or as part of the nodes grid function in the `ParGridFunction` field `Vector face_nbr_data`. In `ParFiniteElementSpace`, the method `GetFaceNbrElementVDofs` can be used to determine which are the face-neighbor dofs corresponding to a given face-neighbor element. For example, see how these methods are used in `ParBilinearForm::AssembleSharedFaces`....</small>

<a href='https://github.com/mfem/mfem/issues/4853' target='_blank'>View Comment</a>