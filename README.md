# CMS-Octree-Implementation
A CMS mesh generator implementation in parallel on the GPU with integration to an Octree allowing varying levels-of-detail (LODs).
Octree creation happens in parallel on the GPU and is stored in a 3D texture on the GPU for access in mesh generation

(Still in development)

Bugs: Holes appear in mesh between Octree levels upon regenerating an already generated mesh (possibly some sort of caching issue on the GPU)
