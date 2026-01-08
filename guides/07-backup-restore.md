# Backup and Restore

Components to protect:
- ETCD (cluster state)
- PVC snapshots (persistent data)
- Cluster config and manifests in Git

Tools: Velero for backups, Velero plugins for cloud providers, etcd snapshotting for control plane.

Restore drills: automate restore tests and schedule regular recovery exercises.
