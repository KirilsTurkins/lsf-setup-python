# LSF maintained action security fork

Based on actions/setup-python v7.1.0 at 6d4fd22b20465ccc0f7354476588e8df7c9ca0e0.

The runtime dependency graph is pinned to patched package versions and the action bundles are rebuilt from that lock. The public npm registry is used for mirrored development tarballs with their original integrity retained.

Validation: Node 24.19.0 on Linux, locked installation, upstream build and the available upstream unit-test suite. Runtime OSV scan: zero findings in 46 packages. Exact bundle hashes and dependency selections are recorded in LSF-SECURITY.json.

This work was discovered while hardening CI for [Latent Service Fabric (LSF)](https://github.com/KirilsTurkins/latent-service-fabric) and is being contributed upstream. Upstream licenses and source history are retained.
