# contract-guest-common

The shared headers the dress-on guests include: blake3 and the mesh wire format.

Split out of `interactor-dress-on` at `310b52e` with its history (`git subtree`). It sits at `2-contract/guest-common` in the goal manifest (`contract-manifest-taskweft`), and finds the repositories it builds against as sibling checkouts at their manifest paths. `transport-meshing-pen` builds the guest ELFs (`build.sh`, `tools/build.exs`).
