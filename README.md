# contract-guest-common

Shared C++ code the sandboxed guest programs include: a BLAKE3 hash, the mesh wire format and a triangle BVH for geometry queries.

## What it is for

Guests hash what they read or compute with the checksum the host compares, pass meshes and curves across the host boundary in one packed layout, and answer closest-point and ray queries from one implementation, so no stage carries its own copy. It has no build of its own: the goal manifest checks it out beside the repositories that include it, and `transport-meshing-pen` builds the guest programs.

## Licence

There is no licence file. The geometry-query files carry `Apache-2.0 OR MIT` SPDX headers; the other headers state no licence.
