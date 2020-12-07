# Kubernetes Master Class: Single Pane of Glass

This repository contains the technical material to go along with [this](https://info.rancher.com/kubernetes-master-class-dec8-2020) class.

## Architecture

The examples provided in this registry will install the observer model for the Thanos operator and the primary remote model for Istio.

As such the "Single Pane of Glass" can manage orchestration of infrastructure and applications (Rancher), monitoring (Thanos), and service mesh (Istio).

## Structure

./primary_observer: Central Control Cluster

./primary_observer/prerequisites 

./primary_observer/istio

./primary_observer/thanos

./remote_workload: Distributed Workload Clusters

./remote_workload/prerequisites

./remote_workload/istio

./remote_workload/thanos
