# contract-guest-common

The shared code the stage guests include: blake3, the mesh wire format and the hf_geom triangle BVH.

Split out of `interactor-dress-on` at `310b52e` with its history (`git subtree`). It sits at `2-contract/guest-common` in the goal manifest (`contract-manifest-taskweft`), and finds the repositories it builds against as sibling checkouts at their manifest paths. `transport-meshing-pen` builds the guest ELFs (`build.sh`, `tools/build.exs`).
