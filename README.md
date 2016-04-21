HTC VIVE Template (soon to be general VR template)

It seems the community is in need of a quality HTC Vive Template till Epic Games gets their official ones going.


GitHub Download: 

Version 1.0

Features:

-Smallest VR Project EVER: So far the total project size is about 6MB, WHAT?!
-Preset Rendering Settings: Don't have to go into 'Project Settings' and change anything.
-Trackpad Input Bindings included for non-room scale locomotion
-VR-Physics World: Go have some fun with picking up and throwing objects!


General Changes:

-Added HTC Vive motion controller static meshes for "hands"
-Target Hardware: Set to mobile w/ scalable 2D and 3D (this is how you achieve 6Mb project file size)

Render Settings Changes:

-Default Postprocessing Settings: All Disabled (enable if you really need them...)
-Optimization Changes: Early Z-pass set to 'Opaque Meshes Only,' Movables in early Z-Pass enabled, Clear Scene set to 'Do Not Clear,' with Vertex Deformation and GBuffer rendertargets disabled
-Instant Stereo Rendering: Enabled
-Framerate Settings: Smooth rate, min 90, max 120, min desired 90 (this one is debatable depending on who you talk to)

VR-PhysicsWorld:

-Postprocessing volume preset (no bloom, SSRs, etc.)
-Basic material that has been instanced
-Physics Cube Actors to interact with (pickup, throw, etc.)


The download link is at the top of this post. It is on a public GitHub repo and community involvement would be awesome to see. I plan on making a shooting range and a few other levels so if anyone wants to beat me to those and add them to this project (regardless of it being Vive or Oculus based) then go right ahead :)
