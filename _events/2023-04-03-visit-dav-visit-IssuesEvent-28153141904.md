---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2023-04-03
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/491
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> closed issue <a href='https://github.com/visit-dav/visit/issues/491' target='_blank'>visit-dav/visit#491</a>.

<p>MDS Server - restoring session reader errors.</p><small>I have a session file with three files with specific readers specified, visit can not open one of the three but then continues to try with other readers. The session file xml: <Field name="localhost:/Projects/Data/Fusion/NIMROD/87009/phi_BT.h5" type="string">"H5Nimrod_1.0"</Field> <Field name="localhost:/Projects/Data/Fusion/Siesta/siesta_cdx.silo.h5" type="string">"Silo_1.0"</Field> <Field name="localhost:/Projects/latex_it" type="string">"MDSplus_1.0"</Field> The last file being read is going to throw InvalidFilesException - which is correct. VisIt imported a session from: /Projects/VisIt/trunk/src/LineSampler.session.Shortly thereafter, the following occured...VisIt could not read from the file "/Projects/latex_it".The generated error message was:There was an error opening /Projects/latex_it. It may be an invalid file. VisIt tried using the following file format readers to open the file: MDSplus However, then for unknown reasons VisIt tries to open the file using the H5Nimrod reader not once but twice. First errant reading: Shortly thereafter, the following occured...VisIt cannot read the SIL for the file "/Projects/latex_it" on host localhost.The metadata server returned the following message:There was an error opening /Projects/latex_it. It may be an invalid file.VisIt tried using the following file format readers to open the file: H5NimrodIf you know the specific format reader VisIt should use toread this data, you can use Open As... (GUI) or'-o <file>,<plugin> (CL arg.) and identify that specific readerfor VisIt to try. This will possibly give more information onthe exact error. Second Errant reading: Shortly thereafter, the following occured...VisIt could not read from the file "/Projects/latex_it".The generated error message was:There was an error opening /Projects/latex_it. It may be an invalid file.VisIt tried using the following file format readers to open the file: H5NimrodIf you know the specific format reader VisIt should use toread this data, you can use Open As... (GUI) or'-o <file>,<plugin> (CL arg.) and identify that specific readerfor VisIt to try. This will possibly give more information onthe exact error. Then, after trying to examine the Active source list, it tries all of the readers in the preferred list twice. (Error below) VisIt could not read from the file "/Projects/latex_it".The generated error message was:There was an error opening /Projects/latex_it. It may be an invalid file.VisIt tried using the following file format readers to open the file: GTC, H5Nimrod, H5Part, M3D, M3DC1, VsIf you know the specific format reader VisIt should use toread this data, you can use Open As... (GUI) or'-o <file>,<plugin> (CL arg.) and identify that specific readerfor VisIt to try. This will possibly give more information onthe exact error. Shortly thereafter, the following occured...VisIt cannot read the SIL for the file "/Projects/latex_it" on host localhost.The metadata server returned the following message:There was an error opening /Projects/latex_it. It may be an invalid file.VisIt tried using the following file format readers to open the file: GTC, H5Nimrod, H5Part, M3D, M3DC1, VsIf you know the specific format reader VisIt should use toread this data, you can use Open As... (GUI) or'-o <file>,<plugin> (CL arg.) and identify that specific readerfor VisIt to try. This will possibly give more information onthe exact error. So it would seem that if a reader is specified in a restored session file and it fails then VisIt should quit rather than trying other readers????? Next, it seems that the active source list is screwed up because of the above error. The active source list shows one file: siesta_cdx.silo.h5 which would appear to have been opened correctly because multiple plots are drawn based on it. However, "File Info" say there are no open files. Further, "Plots Add" is deactivated. So at least there is consistency in VisIt being wrong. It is possible to reopen the file siesta_cdx.silo.h5 and have the "File Info" correct and the "Plots Add" active. Finally, visit continues to try and open the file and reports the error - it needs to quit....</small><a href='https://github.com/visit-dav/visit/issues/491' target='_blank'>View Comment</a>