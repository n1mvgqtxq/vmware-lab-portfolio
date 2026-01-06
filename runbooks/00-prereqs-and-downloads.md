# 00 Prerequisites and Downloads

## Goal
Prepare a VMware home lab environment to demonstrate administration of vCenter, vSAN, NSX, and Kubernetes.

## Local System Requirements
- CPU virtualization enabled in BIOS or UEFI (Intel VT-x or AMD-V).
- Recommended RAM: 32 GB minimum (64 GB preferred for NSX plus Kubernetes).
- Recommended free SSD space: 500 GB or more.

## Software Required
1. VMware Workstation Pro (host hypervisor for the lab).
2. VMware ESXi ISO (for nested ESXi hosts).
3. vCenter Server Appliance (VCSA) ISO.
4. NSX Manager OVA (or unified NSX download if provided).
5. Linux ISO for Kubernetes nodes (Ubuntu Server LTS recommended).

## Accounts and Access
- Create a Broadcom Support Portal account if needed for VMware downloads.
- Keep all license keys out of GitHub. Use evaluation mode or VMUG membership where applicable.

## Evidence to Capture
- Screenshot of Workstation Pro version page.
- Screenshot of nested ESXi host UI login page.
- Screenshot of vCenter inventory after deployment.
- Screenshot of vSAN health summary after enabling.
- Screenshot of NSX Manager dashboard after deployment.
- Screenshot of `kubectl get nodes` after Kubernetes cluster build.

## Notes
- This repository documents lab-only work intended as proof of skill development and operational practice.
- No secrets, tokens, passwords, or license keys should be committed.
