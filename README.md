# Xloud Unified Storage

Xloud Unified Storage is the working repository for a Kubernetes-native storage
platform for Xloud environments. The goal is to provide one operational storage
layer for block, file, and object workloads across cloud, edge, and OpenStack
integrated deployments.

## Goals

- Unified block, file, and object storage for Kubernetes and OpenStack.
- Tenant-aware provisioning, quotas, snapshots, clone, backup, and restore.
- Storage policy automation for performance, availability, encryption, and data
  locality.
- Health, capacity, alerting, and lifecycle visibility through Xloud control
  planes.
- A practical foundation on proven open-source storage engines before custom
  control-plane work.

## Initial Direction

The first architecture track should evaluate and prototype:

- Rook/Ceph for block, file, and S3-compatible object storage.
- Longhorn for lightweight edge block-storage use cases.
- OpenEBS Mayastor for high-performance NVMe/SPDK paths.
- Xloud-specific operator and API layers for policy, tenancy, automation, and
  UI integration.

## Repository Status

This repository is new. Initial work should start with architecture notes,
lab topology, OSS evaluation, and a minimal deployable prototype.
