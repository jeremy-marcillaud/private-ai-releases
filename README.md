<!-- Kept in jeremy-marcillaud/ai-setup-vm at release/releases-repo/README.md and pushed here by
     the Release workflow on each tag. Edit it there: a change made here is overwritten. -->

# private-ai-releases

Download packages for **Private AI**: the installer, the agent and the chart that run on a customer's own machine.

This repository holds release downloads only. It contains no source code. Each release has two files:

- `private-ai-<version>.tar.gz`: the package
- `private-ai-<version>.tar.gz.sha256`: its checksum

Customers do not download these by hand. The Private AI dashboard shows a one-line install command that fetches and verifies the right release.

**Supported platform:** Ubuntu 24.04 on `x86_64` and `aarch64` (arm64).

See [LICENSE](LICENSE). All rights reserved.
