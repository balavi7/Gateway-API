# Kubernetes Gateway API – Traffic Management Demo

This repository contains hands-on examples demonstrating how to use the **Kubernetes Gateway API** with **Envoy Gateway** to manage application traffic efficiently.

The project covers multiple real world routing scenarios including **host based routing, header based routing, rewrite URL, traffic splitting, weighted routing, and TLS termination**.

---

## What This Repository Covers

✔️ Installation of Envoy Gateway  
✔️ GatewayClass and Gateway configuration  
✔️ HTTPRoute examples  
✔️ Host-based routing  
✔️ Header-based routing  
✔️ rewrite URL
✔️ Traffic splitting & weighted routing  
✔️ TLS configuration using self-signed certificates  
✔️ End-to-end testing using `curl`

---

## Prerequisites

Make sure you have the following installed:

- Kubernetes cluster (Minikube / Kind)
- kubectl
- Helm
- curl
- Basic understanding of Kubernetes networking

---

## Repository Structure

```bash
.
├── 01-install/                # Installing CRDs and Envoy Gateway
├── 02-deploy-codes/           # Basic manifest files
├── 03-rewrite_url/            # httproute file
├── 04-traffic-splitting/      # backend-2 and httproute file
├── 05-weighted/               # httproute file    
├── 06-host-based/             # backend and httproute file
├── 07-header-based/           # backend and httproute file
├── 08-TLS/                    # TLS certificates and httproute file
├── LICENSE         
└── README.md
