# Nexus platform service registry

Top-level directories are platform partitions. Each partition keeps its
service descriptors under `services/`; descriptor files are YAML and are
maintained by the owning team. Partitions are never renamed and descriptors
are never moved between partitions.

`governance/` holds the policy index for the registry. It is not a platform
partition.
