---
layout: default
title: "How we'll do it?" 
---


# How can we make this happen
## Core architecture
1 Voxel = 1 m3

1 Chunk = 32.768 m3

# Chunks
Each chunk will be a Box measuring 32 Voxels each side. 



Chunks will only display what's visible to the player (frustum culling). 



Chunks will be compressed for storage to save space. 



Chunks will gather all Naturally Generated Voxels with same id into a single structure to enhance Storage

Structures
To enhance Storage, in the following releases, users wi be able to solidify a structure by selecting it, naming it and categorizing it, so that it gets saved to storage as a single Unit and more features that will be discussed when time comes.

