# Cross Solution Network Architectures

This is a repo of cross solution network connectivity designs with Azure PaaS services, Azure Kubernetes Services(AKS) and on-premise connectivity. These designs are based on real world experiences working with partners,customers and cross solution CSAs in various ADS (Azure Design Sessions). This repo will contain downloadable artifacts like bicep automated deployments, architecture diagrams, postman collections and tools to test applications for various designs. Learn about tools of trades from various SME CSAs to validate designs,connectivity, view application and traffic flows.

# Design Areas

### Advanced Linux Networking

- [VXLAN with two linux hosts (As good as it gets!)](advanced-linux-networking/linux-vxlan.md)
- BIRD Internet Routing Daemon (BGP Routing on linux) (Coming Soon...)
- Openswan VPN (IPsec Tunnels)
- The perfect NVA with linux
- IPtables and eBPF
- Cluster Networking - [IPVLAN, MACVLAN, TUN/TAP drivers](https://kubernetes.io/docs/concepts/cluster-administration/networking/)

### [Azure Kubernetes Services (AKS) Networking Series](aks/README-advanced.md)

- [Docker Networking](aks/README-docker-multihost.md)
  - [Single Host](aks/README-docker-singlehost.md)
  - [Multi Host](aks/README-docker-multihost.md)
  - Bicep automated deployment (Coming soon...)
  - kind Cluster (Kubernetes In Docker)
- [Basic/Kubenet Networking](aks/README-kubenet.md)
- [Advanced/Azure CNI Networking](aks/README-advanced.md)
- [AKS Private Cluster](aks/README-private-cluster.md)
  - [AKS Private Cluster with Azure Front Door](aks/README-private-cluster-with-AFD.md)
- [Ingress Controllers](aks/README-ingress-appgw.md)
  - [AKS Application Gateway Ingress Controller (AGIC)](aks/README-ingress-appgw.md)
  - [Nginx Ingress controller](aks/README-ingress-nginx.md)
- [AKS Egress with Azure firewall/NVA](aks/README-aks-egress.md)
- [AKS Multiple Nodepool Design](aks/README-multinode.md)
- Core DNS and Azure DNS Integrations (Coming soon...)
- Kubernetes Network Model - Multus, Flannel,Weave, Calico, Cilium
- Kubernets Serivce Mesh (Istio, Linkerd and Consul)

### [Azure Database Services](database-services/README.md)

- [SQL Managed Instance](database-services/README.md)
  - Single Region (database-services/README.md)
  - Multi region with Replication - DR Scenario (Coming Soon...)
  - Database failover with Application connectivity
- [Azure Data Factory(ADF)](database-services/README-ADF.md)
  - Managed VNET and Private Endpoints
  - Self hosted Integration Runtime (IR) In Azure
  - Self hosted Integration Runtime (IR) On Premises
- Azure SQL Database (PaaS Service)
- Azure Synapse
- OSS databases - mysql and postgres

### [Azure API Management(APIM) Networking Series](apim/README.md)

- [APIM Big Picture view](apim/README-common.md)
- [Default mode](apim/README-default.md)
- [External network mode](apim/README-external.md)
- [Internal network mode](apim/README-internal.md)
- [Internal network mode with Azure Application Gateway](apim/README-appgw.md)
- [APIM with Azure firewall/NVA](apim/README-firewall.md)
- [APIM Identity - AAD and B2C Integration](apim/README-identity.md)
- [APIM Multi-region Architecture](apim/README-mulitregion.md)
- [Self hosted gateway](apim/README-internal.md#api-self-hosted-gateway)
- [LetsEncrypt Certificates and APIM Custom Domain](apim/README-custom-domain.md)
- [Azure Private DNS Zones integration](apim/README-custom-domain.md)
- [Network Troubleshooting](apim/README-troubleshooting.md)
- [Download Postman Collection](apim/README-postman.md)
- Download [Multi-tab Visio](apim/APIM-all-reference-architectures-visio.vsdx) and [PDF](apim/APIM-all-reference-architectures-PDF.pdf) of all APIM Networking Architectures

### [Azure App-service Networking ](app-service/README.md)

- [Private Endpoint Integration](app-service/README.md)
- [Service Endpoint](app-service/README.md)
- [VNET Integration](app-service/README.md)
- [NAT Gateway Integration](app-service/README.md)
- [Azure Private DNS Zone Planning](app-service/README.md)
- Azure App-Service with firewall for outbound traffic filtering (coming soon!)

### DevOps and Automation

- Bicep Automated deployments (Coming Soon...)
- Azure DevOps
- GitOps for Application deployment
- CI/CD pipelines using Github Actions

# Tools of Trade (Work in progress)

0. VSCode Extentions

1. Database

   - SQl Server Management Studio (SSMS)
   - Azure Data Management Studio

2. Networking

   - Microsoft Whiteboard
   - Linux Networking
   - Wireshark/tcpdump
   - dig
   - hping, tcptraceroute

3. Application
   - python
   - html
   - node.js
   - mysql
4. DevOps
   - github
   - Postman

# Build Sample Applications (Work in progress)

1. Simple CRUD API Application
2. Simple http server
3. Simple 3-tier application for AKS

## Contributors

Special thank you to my collegues

- [David O'Keefe](https://www.linkedin.com/in/david-o-keefe/)
- [Shaun Croucher](https://github.com/shcrouch)
- [Xavier Elizondo](https://github.com/xelizondo)
- [Heather Tze](https://github.com/hsze)
- [Daniel Mueser](https://github.com/dmauser)
- [Sowmyan Soman Chullikkattil](https://github.com/sowsan)
- [Mike Richter](https://github.com/michaelsrichter)
- [Sumit Sengupta](https://github.com/sumitsengupta)
- [Mike Shelton](https://www.linkedin.com/in/mshelt)
- [Tommy Falgout](https://github.com/lastcoolnameleft)
- [Devanshi Joshi](https://github.com/devanshidiaries)

## Acknowledgments
