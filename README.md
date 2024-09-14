# Multi-Node-Clusters-Kind

This repository contains a simple example of a multi-node Kubernetes cluster using Kind (Kubernetes IN Docker). The cluster is configured with one control plane node and two worker nodes.

## Prerequisites

- Docker
- Kind
- kubectl

## Creating the Cluster

To create the cluster, run the following command:

```bash
kind create cluster --config cluster.yaml
```

This will create a three-node cluster with one control plane and two worker nodes.

## Accessing the Cluster

To interact with the cluster, you can use the `kubectl` command-line tool. For example, to list the nodes in the cluster, run:


