# Production repository

This is the R-multiverse Production repository.

Production snapshots happen automatically.
`snapshot.yaml` runs on a [quarterly schedule](https://r-multiverse.org/production.html#schedule) and commits configuration files to the [`snapshot`](https://github.com/r-multiverse/production/tree/snapshot) branch.
On each commit to the [`snapshot`](https://github.com/r-multiverse/production/tree/snapshot) branch, [Netlify](https://www.netlify.com) downloads and publishes a snapshot of the [Staging](https://staging.r-multiverse.org) universe.

For all matters, please refer to <https://r-multiverse.org>.
