# Naming Standards

## Purpose
Establish consistent naming for hosts, clusters, networks, and workloads to improve troubleshooting, reporting, and documentation clarity.

## VMware Objects
- vCenter: vcsa01
- Datacenter: DC01
- Cluster: CL01
- ESXi hosts: esx01, esx02, esx03
- Distributed switch: vds01
- Port groups: pg-mgmt, pg-vmotion, pg-vsan, pg-uplink

## vSAN
- Disk groups: dg01, dg02 (per host if needed)
- Datastores: vsanDatastore

## NSX
- NSX Manager: nsxmgr01
- Segments: seg-mgmt, seg-app, seg-k8s
- Security groups: sg-admin, sg-app
- Policies: pol-baseline-segmentation

## Kubernetes
- Control plane: k8s-cp01
- Workers: k8s-wk01, k8s-wk02
- Namespaces: platform, apps, monitoring
