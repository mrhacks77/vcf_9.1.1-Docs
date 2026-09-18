# VMware Cloud Foundation 9.1.1 — Documentation Reference Index

This is the AI/quick-reference index for the full VCF 9.1.1 documentation PDF (9,401 pages). Claude.ai enforces a **1,000-page limit per PDF** (regardless of file size), so the doc is split into **11 files**, each under 950 pages and well under the 30MB size cap too.

| # | File | Pages | Size | Covers |
|---|---|---|---|---|
| 1 | `VCF-9.1.1_Part01_ReleaseNotes-Overview-Design.pdf` | 800 | 6MB | VMware Cloud Foundation 9.1, Contents, Release Notes, Overview, Design |
| 2 | `VCF-9.1.1_Part02_DesignBlueprints.pdf` | 909 | 9MB | Design Blueprints for VMware Cloud Foundation |
| 3 | `VCF-9.1.1_Part03_Planning-Deployment-Licensing.pdf` | 950 | 9MB | Design Library detailed designs, Planning and Preparation, Deployment/Convergence/Upgrade, Licensing |
| 4 | `VCF-9.1.1_Part04_BuildingCloudInfra-vSphere-vSAN-NSX.pdf` | 933 | 8MB | Building Cloud Infrastructure, vSphere, vSAN, NSX (start) |
| 5 | `VCF-9.1.1_Part05_Lifecycle-Fleet-InfraOpsStart.pdf` | 946 | 4MB | rest of NSX, Lifecycle Management, Fleet Management, Infrastructure Operations (start) |
| 6 | `VCF-9.1.1_Part06_InfraOps-Alerts-Inventory-Logs.pdf` | 928 | 6MB | rest of Infrastructure Operations (Alerts, Inventory, Logs, Network Operations, Diagnostics, Workbench, Dashboards/Widgets) |
| 7 | `VCF-9.1.1_Part07_WorkloadMonitoring.pdf` | 887 | 5MB | rest of VCF Operations dashboards/metrics/management packs, Workload Monitoring and Observability |
| 8 | `VCF-9.1.1_Part08_CostCapacity-Mobility-Security-Supervisor-Provider-Org.pdf` | 945 | 8MB | Cost and Capacity Management, Workload Mobility (HCX), Security and Compliance, vSphere Supervisor Platform, Provider Management, Organization Management (start) |
| 9 | `VCF-9.1.1_Part09_Orchestration-CloudApps-PrivateAI-SDKs.pdf` | 874 | 6MB | rest of Organization Management (VM Apps), Workload Orchestration, Building Cloud Applications, Private AI, Administration SDKs/APIs/CLI (start) |
| 10 | `VCF-9.1.1_Part10_AdminSDKs-APIs-CLI.pdf` | 935 | 6MB | VCF Programming Guide, VCF PowerCLI, VCF Operations API |
| 11 | `VCF-9.1.1_Part11_AdvancedServices-Index.pdf` | 294 | 1MB | VCF Operations for Networks API Guide, VCF Automation APIs, Advanced Services, Index |

## How to use these files
Each part's PDF lives in this same folder, named exactly as in the table above.
To answer a question: find the closest matching heading in the detailed TOC below, note its page number, then open that page in the matching split PDF.

## Top-level chapters (original 9,401-page document)

| Chapter | Original page | Split file (local page) |
|---|---|---|
| VMware Cloud Foundation 9.1 | 1 | Part01 (p.1) |
| Contents | 2 | Part01 (p.2) |
| Release Notes | 77 | Part01 (p.77) |
| Overview | 682 | Part01 (p.682) |
| Design | 718 | Part01 (p.718) |
| Design Blueprints | (within Design) | Part02 (p.1) |
| Design Library (detailed designs) | (within Design) | Part03 (p.1) |
| Planning and Preparation | 2400 | Part03 (p.691) |
| Deployment, Convergence, and Upgrade | 2410 | Part03 (p.701) |
| Licensing | 2617 | Part03 (p.908) |
| Building Cloud Infrastructure | 2665 | Part04 (p.6) |
| vSphere | 2800 | Part04 (p.141) |
| vSAN | 2802 | Part04 (p.143) |
| NSX | 3053 | Part04 (p.394) |
| NSX (continued: monitoring, auth, certs, troubleshooting) | (within NSX) | Part05 (p.1) |
| Lifecycle Management | 3934 | Part05 (p.342) |
| Fleet Management | 3980 | Part05 (p.388) |
| Infrastructure Operations | 4458 | Part05 (p.866) |
| Infrastructure Operations (continued) | (within Infra Ops) | Part06 (p.1) |
| Workload Monitoring and Observability | 6350 | Part07 (p.884) |
| Cost and Capacity Management | 6480 | Part08 (p.127) |
| Workload Mobility | 6584 | Part08 (p.231) |
| Security and Compliance | 6775 | Part08 (p.422) |
| vSphere Supervisor Platform | 6802 | Part08 (p.449) |
| Provider Management | 7038 | Part08 (p.685) |
| Organization Management | 7164 | Part08 (p.811) |
| Organization Management (continued: VM Apps) | (within Org Mgmt) | Part09 (p.1) |
| Workload Orchestration | 7741 | Part09 (p.443) |
| Building Cloud Applications | 7902 | Part09 (p.604) |
| Private AI | 8116 | Part09 (p.818) |
| Administration SDKs, APIs, and CLI | 8117 | Part09 (p.819), continues Part10 (p.1) |
| Advanced Services | 9398 | Part11 (p.291) |
| Documentation Legal Notice | 9400 | Part11 (p.293) |

---

# Detailed Table of Contents (all parts)

## Part 1: VCF-9.1.1_Part01_ReleaseNotes-Overview-Design.pdf (800 pages)
Covers: VMware Cloud Foundation 9.1, Contents, Release Notes, Overview, Design
Page numbers (p.N) are local to this file.

- VMware Cloud Foundation 9.1 — p.1
- Contents — p.2
- Release Notes — p.77
  - VMware Cloud Foundation 9.1.0 Release Notes — p.77
    - Upgrade Sequence to 9.1 — p.77
    - What's New — p.78 (vSphere p.79, vSAN p.86, NSX p.88, VCF Installer p.94, VCF Operations p.95, VCF Automation p.107, VCF SDKs/APIs/CLIs p.109)
    - Bill of Materials 9.1.0 — p.499
    - Product Support Notes — p.502
    - Known Issues — p.511
    - Resolved Issues — p.547
  - VMware Cloud Foundation 9.1.1 Release Notes — p.563 (vCenter p.567, ESX p.574, vSAN p.604, NSX p.606, VCF Installer/SDDC Manager p.610, VCF Operations p.613, VCF Automation p.629, VCF SDKs/APIs/CLIs p.635)
  - Patch Releases 9.1.0.x — p.646
  - Async Releases — p.680
- Overview — p.682
  - What Is VMware Cloud Foundation? — p.682 (VCF Installer Overview p.684, vSphere Overview p.685, vSAN Overview p.685, NSX Overview p.686, VCF Operations Overview p.687, VCF Automation Overview p.699)
  - What Is vSphere Foundation? — p.700
  - VCF Taxonomy — p.701
  - VCF Capabilities by Job Function — p.704
  - Getting Started with VMware Cloud Foundation — p.707
  - Getting Started with vSphere Foundation — p.716
- Design — p.718
  - Architectural Options in VMware Cloud Foundation — p.719
    - VCF Fleet Deployment Models — p.720
    - VCF Fleet Sizing Models — p.732
    - VCF Automation Models — p.733
    - vSphere Supervisor Models — p.735
    - Network Consumption Models — p.747
    - Workload Connectivity Models — p.750
    - Load Balancer Models — p.754
    - VCF Management Services Models — p.757
    - VCF Management Network Models — p.759
    - VCF Operations Models — p.760
    - VCF Recovery Options — p.768
    - Identity Broker Models — p.769
    - VCF Domain Models — p.772
    - vSphere Cluster Models — p.774
    - Distributed Switch Models — p.776
    - Storage Models — p.780
    - NSX Manager and Control Plane Models — p.786
    - NSX Edge Cluster Models — p.788
    - Virtual Network Appliance Cluster Models — p.791
    - Network Fabric Models — p.793
    - VCF Edge Models — p.796
    - Private AI Foundation Platform Models — p.796
    - Private AI Foundation Compute Models — p.797
    - Lateral Security with vDefend Models — p.799

## Part 2: VCF-9.1.1_Part02_DesignBlueprints.pdf (909 pages)
Covers: Design Blueprints for VMware Cloud Foundation
Page numbers (p.N) are local to this file.

- Design Blueprints for VMware Cloud Foundation — p.1
  - Infrastructure Modernization — p.3
    - VCF Fleet in a Single Site with Minimal Footprint — p.5
    - VCF Fleet in a Single Site — p.72
    - VCF Fleet with Multiple Sites in a Single Region — p.158
    - VCF Fleet with Multiple Sites Across Multiple Regions — p.255
    - VCF Fleet with Multiple Sites in a Single Region plus Additional Region(s) — p.343
    - VCF Fleet Management Blueprint — p.475
    - VCF Monitoring and Alerting Blueprint — p.508
    - VCF Troubleshooting Blueprint — p.516
    - VCF Edge: Single Node with Argo CD Design Blueprint — p.532
    - VCF Edge Design Blueprint for Government and Defense Use Case — p.566
    - VCF Edge Design Blueprint for Manufacturing Use Case — p.619
  - Application Modernization — p.647
    - Self-Service Multi-Tenant Private Cloud Consumption Design Blueprint — p.648
    - VMware vSphere Kubernetes Service Consumption Blueprint — p.718
    - Private AI Services Consumption Blueprint — p.751
  - Security Modernization — p.780
    - VCF Component Backup and Restore — p.780
    - VCF Instance Backup and Restore — p.785
    - VCF Fleet Disaster Recovery — p.790
    - Cyber Recovery for VMware Cloud Foundation — p.797
    - Lateral Security with vDefend — p.811

## Part 3: VCF-9.1.1_Part03_Planning-Deployment-Licensing.pdf (950 pages)
Covers: Design Library detailed designs, Planning and Preparation, Deployment/Convergence/Upgrade, Licensing
Page numbers (p.N) are local to this file.

- Design Library for VMware Cloud Foundation — p.1
  - VCF Automation Detailed Design — p.1
  - vSphere Supervisor Detailed Design — p.75
  - VMware Data Services Manager Detailed Design — p.94
  - Workload Connectivity Detailed Design — p.105
  - Load Balancer Detailed Design — p.202
  - VCF Management Services Component Detailed Design — p.224
  - VCF Management Services Detailed Design — p.227
  - VCF Management Network Detailed Design — p.231
  - VCF Operations Detailed Design — p.246
  - License Server Detailed Design — p.299
  - Identity Broker Detailed Design — p.301
  - VCF Single Sign-On Detailed Design — p.305
  - Information Security Detailed Design — p.312
  - VCF Domain Detailed Design — p.320
  - vSphere Detailed Design — p.325
  - vSphere Cluster Detailed Design — p.330
  - VCF Network Detailed Design — p.352
  - Storage Detailed Design — p.386
  - NSX Manager and Control Plane Detailed Design — p.476
  - NSX Edge Cluster Detailed Design — p.493
  - Virtual Network Appliance Cluster Detailed Design — p.543
  - External Services Detailed Design — p.578
  - Data Center Network Requirements — p.578
  - VCF Edge Detailed Design — p.612
  - Private AI Platform Detailed Design — p.651
  - Private AI Compute Detailed Design — p.671
- Planning and Preparation — p.691
  - Public URLs Required for Online Functionalities for VCF and vSphere Foundation — p.691
  - VCF Components FQDNs and IP addresses — p.693
  - Network Deployment Options for VCF Components — p.699
- Deployment, Convergence, and Upgrade — p.701
  - Paths to Building 9.1.x Environments — p.701
  - Components in VCF and vSphere Foundation — p.703
  - Deploying a New VCF or vSphere Foundation Platform — p.708
  - Converging Existing Virtual Infrastructure to a VCF or a vSphere Foundation Platform — p.790
  - Upgrading to VMware Cloud Foundation 9.1.x — p.812
    - Upgrading to VCF Operations 9.1 — p.817
    - Upgrading to VCF Automation 9.1 — p.835
    - Upgrading to VCF Operations for Networks 9.1 — p.848
    - Upgrade the Remaining Components in the Management Domain to 9.1 — p.855 (Upgrading vCenter and NSX Manager p.859, Transitioning vLCM Baselines to Images p.870, Upgrade ESX to 9.1 p.895)
  - Upgrading to vSphere Foundation 9.1.x — p.901
- Licensing — p.908
  - Licensing Overview — p.908
  - License Server Overview — p.918
  - Registering VCF Operations and a License Server with the VCF Business Services Console — p.923
  - Managing Licenses in the VCF Business Services Console — p.933
  - Add/Assign/Override/Remove Licenses — p.935-945
  - License Usage Analytics — p.949

## Part 4: VCF-9.1.1_Part04_BuildingCloudInfra-vSphere-vSAN-NSX.pdf (933 pages)
Covers: Building Cloud Infrastructure, vSphere, vSAN, NSX (start)
Page numbers (p.N) are local to this file.

- License Management for Cloud Services Providers and Hyperscalers — p.1
- Building Cloud Infrastructure — p.6
  - Managing ESX Hosts in VMware Cloud Foundation — p.6
  - Managing VCF Domains in VMware Cloud Foundation — p.14 (Create Workload Domain p.15, Expand VCF Domain p.39, Shrink Workload Domain p.50)
  - Stretching vSAN Clusters in VMware Cloud Foundation — p.55
  - Managing Network Connectivity in vCenter — p.95
  - Managing Virtual Private Clouds in vCenter — p.108
  - SDDC Manager Workflows in VMware Cloud Foundation 9.1 — p.140
- vSphere — p.141
- vSAN — p.143
  - Designing vSAN Network — p.143
  - Planning and Configuring vSAN — p.189
  - Administering VMware vSAN — p.246
  - Monitoring and Troubleshooting vSAN — p.348
- NSX — p.394
  - NSX Manager — p.395
  - Tier-0 Gateways — p.398
  - Tier-1 Gateway — p.449
  - Segments — p.452
  - NSX DHCP — p.478
  - Host Switches — p.501
  - Transport Zones and Profiles — p.541
  - Host Transport Nodes — p.560
  - Installing NSX Edge — p.579
  - Setting up Network Connectivity — p.632
  - Virtual Private Cloud in NSX — p.640
  - Virtual Private Network (VPN) — p.676
  - Network Address Translation (NAT) — p.713
  - NSX Native Load Balancer — p.720
  - Ethernet VPN (EVPN) — p.753
  - IP Address Management (IPAM) — p.782
  - Networking Settings — p.788
  - vDefend Firewall with Advanced Threat Prevention — p.794
  - Inventory — p.794
  - Multisite and NSX Federation — p.816
  - NSX Multi-tenancy — p.875

## Part 5: VCF-9.1.1_Part05_Lifecycle-Fleet-InfraOpsStart.pdf (946 pages)
Covers: rest of NSX (monitoring/auth/certs/troubleshooting), Lifecycle Management, Fleet Management, start of Infrastructure Operations
Page numbers (p.N) are local to this file.

- System Monitoring — p.1
- Network Monitoring — p.72
- Authentication and Authorization — p.97
- Certificates in NSX — p.132
- Integration of Kubernetes Clusters with Antrea CNI — p.152
- Backing Up and Restoring NSX Manager or Global Manager — p.203
- Operations and Management — p.211
- Scale Out NSX Manager — p.306
- Troubleshooting Issues — p.324
- Troubleshooting Host Transport Nodes — p.329
- Troubleshooting NSX Edge Nodes — p.334
- NSX Feature and Edition Information — p.340
- Lifecycle Management — p.342
  - Binary Management for VMware Cloud Foundation — p.345
  - Lifecycle Management of VCF Components — p.380
  - Upgrading VMware Cloud Foundation Workload Domains to 9.1.x — p.385
- Fleet Management — p.388
  - Managing Identity and Access With VCF Single Sign-On — p.388
  - Managing Certificates in VMware Cloud Foundation — p.523
  - Managing Passwords for VMware Cloud Foundation Components — p.540
  - Tags and Categories Overview — p.562
  - Managing the Configuration of your Environment — p.571
  - Managing External Infrastructure Services for VMware Cloud Foundation — p.583
  - Adding or Removing VCF Components Post Deployment — p.585
  - Linking vCenter Instances in VCF Operations — p.593
  - Collecting Data with Cloud Proxy in VCF Operations — p.594
  - Shutdown and Startup of VMware Cloud Foundation — p.613
  - Component Backup and Restore of VMware Cloud Foundation — p.631
  - VCF Instance Backup and Restore — p.694
  - VCF Fleet Disaster Recovery — p.789
  - FIPS Configuration for VCF Components — p.849
  - Configuring Management Components — p.854
- Infrastructure Operations — p.866
  - Integrating Data Sources with VCF Operations — p.866
  - Configuring and Managing Policies — p.920

## Part 6: VCF-9.1.1_Part06_InfraOps-Alerts-Inventory-Logs.pdf (928 pages)
Covers: rest of Infrastructure Operations — Alerts, Inventory, Automation Jobs, Logs, Network Operations, Diagnostics, Workbench, Green Score, Dashboards/Widgets
Page numbers (p.N) are local to this file.

- Configuring Alerts and Using Actions — p.1
- Managing Inventory — p.110
- Enhanced Search Capability — p.169
- Configuring Automation Jobs — p.175
- Configuring and Analyzing Logs — p.180
- Network Operations — p.234
  - About VCF Operations for networks — p.235
  - Working with Data Sources — p.237
  - Configuring VCF Operations for networks Settings — p.331
  - Network Assessment and Value Analysis — p.431
  - Backing up/Restoring VCF Operations for Networks — p.432
  - Configuring Flows in VCF Operations for networks — p.439
  - Working with Guided Network Troubleshooting — p.461
  - Entities — p.464
  - Working with Pins and Dashboards — p.494
  - Network Visibility — p.502
  - Working with Network Maps and Intents — p.522
  - Supported Firewalls — p.534
  - Working with Micro-Segmentation — p.540
  - Working with Crown Jewel Analysis — p.545
  - Working with Applications — p.546
  - Working with Analytics — p.565
  - Viewing Recommended Firewall Rules — p.573
  - Working with Search Queries — p.579
  - Working with the Streaming Databus — p.605
  - Metric Definitions in VCF Operations for networks — p.633
  - Troubleshooting and Known Limitations — p.701
- Monitoring Storage Operations — p.716
- Using VCF Operations diagnostics — p.717
- Troubleshooting with the Workbench — p.766
- Configuring Green Score — p.774
- Configuring Dashboards and Widgets — p.787 (Widgets in VCF Operations p.800, Widget Definitions List p.807)

## Part 7: VCF-9.1.1_Part07_WorkloadMonitoring.pdf (887 pages)
Covers: rest of VCF Operations widgets/dashboards, Workload Monitoring and Observability
Page numbers (p.N) are local to this file.

- Using Predefined Dashboards for Quick Insights — p.1 (Application Monitoring, Availability, Capacity, Configuration, Cost, Performance, Private AI, Service Discovery, Inventory dashboards, etc. — p.1-73)
- Configuring Reports and Views — p.74
- Extensions Management — p.107
- Configuring Super Metrics — p.107
- Configuring Administration Settings — p.116 (Managing Users and Access Control in VCF Operations p.124)
- Viewing Metrics and Properties — p.175 (Metric Definitions p.175, Property Definitions p.386)
- Extending Monitoring Capabilities — p.429
  - Installing and Configuring Management Packs (Solutions Catalog) — p.429 (Integrations Configuration Guides: Aggregator, Orchestrator, AWS, VMware Identity Manager, HCX, MSSQL, MongoDB, MySQL, Network Devices, Oracle, PostgreSQL, ServiceNow, Kubernetes, Avi LB, SNMP, VMware Cloud Director, Telco Cloud, vSphere Replication — p.436)
  - Management Pack Builder — p.871
- Workload Monitoring and Observability — p.884
  - Configuring Business Applications — p.884
  - What Are The Different Types of Telegraf Agents in VCF Operations? — p.887

## Part 8: VCF-9.1.1_Part08_CostCapacity-Mobility-Security-Supervisor-Provider-Org.pdf (945 pages)
Covers: Telegraf/Service Discovery monitoring, Cost and Capacity Management, Workload Mobility (HCX), Security and Compliance, vSphere Supervisor Platform, Provider Management, Organization Management (start)
Page numbers (p.N) are local to this file.

- Monitoring Application Services using Product-Managed Telegraf — p.1
- Monitoring Applications Using Open Source Telegraf — p.83
- Discovering Services and Applications using the Service Discovery Adapter — p.114
- Cost and Capacity Management — p.127
  - Configuring Cost — p.127
  - Performing VCF Automation Based Multitenancy in VCF Operations — p.157
  - Optimizing Capacity — p.166
- Workload Mobility — p.231
  - Getting Started with VCF Operations HCX — p.231
  - Administering VCF Operations HCX — p.263 (Site Pairs p.288, Interconnect p.293, Extending Networks p.324, Migrating VMs p.353, System Settings/Certs/Backup/Upgrade/Troubleshooting p.400-419)
- Security and Compliance — p.422
  - Monitoring Security Operations — p.422
  - Viewing and Configuring Compliance — p.425
  - Security Posture Management — p.440
  - Audit Records and Audit Trail — p.445
- vSphere Supervisor Platform — p.449
  - vSphere Supervisor Concepts — p.449
  - Deploying Supervisor with VCF Networking with VPC — p.496
  - Deploying vSphere Supervisor with Foundation Load Balancer — p.512
  - Deploying Supervisor with a Simplified Deployment Flow — p.532
  - Deploying vSphere Supervisor from an Exported Configuration — p.537
  - Configuring and Managing vSphere Namespaces — p.541
  - Configuring and Managing vSphere Zones — p.559
  - Connecting to Supervisor and VKS Clusters — p.562
  - Configuring and Managing a Supervisor — p.568
  - Monitoring vSphere Supervisor — p.600
  - Updating vSphere Supervisor — p.612
  - Backing Up and Restoring vSphere Supervisor — p.629
  - Overview of Running vSphere Supervisor on vSAN Stretched Cluster — p.654
  - Troubleshooting vSphere Supervisor — p.665
- Provider Management — p.685
  - Overview of VCF Automation Provider Management — p.685
  - Managing Identity Providers — p.689
  - Configuring the Access Control — p.710
  - Getting Started with the VCF Automation Provider Management UI — p.740
  - Regions — p.746
  - Create a Content Library — p.750
  - Create an Infrastructure Policy in VCF Automation — p.752
  - Managing Organizations — p.754
  - Managing Networking Resources — p.773
  - Managing System Settings — p.788
  - Managing Certificates — p.794
  - Terraform Configuration in VCF Automation Provider Management — p.796
  - Managing Events and Tasks — p.798
  - Managing Defined Entities — p.799
- Organization Management — p.811
  - Managing Organizations in VMware Cloud Foundation Automation — p.812
  - Getting Started with Organizations in VCF Automation — p.814
  - Managing Identity Providers in VCF Automation Organizations — p.817
  - Managing Predefined User Roles in VCF Automation — p.822
  - Managing Networking in VCF Automation Organizations — p.836
  - Managing Projects in VCF Automation — p.852
  - Setting up the Content Hub in VCF Automation — p.861
  - Managing Blueprints in VCF Automation — p.870
  - Managing Event Subscriptions in VCF Automation — p.898
  - Managing Custom Resources in VCF Automation Blueprints — p.904
  - Managing Policies in VCF Automation — p.906
  - Provisioning Resources in VCF Automation — p.929
  - Administering VCF Automation Organizations — p.930

## Part 9: VCF-9.1.1_Part09_Orchestration-CloudApps-PrivateAI-SDKs.pdf (874 pages)
Covers: rest of Organization Management (VM Apps), Workload Orchestration, Building Cloud Applications, Private AI, Administration SDKs/APIs/CLI (start)
Page numbers (p.N) are local to this file.

- Working with Metadata for VCF Automation Resources — p.1
- Managing Organizations for VM Apps in VMware Cloud Foundation Automation — p.1
  - Getting Started with Organizations in VCF Automation for VM Apps — p.2
  - Working with the catalog in VCF Automation for VM Apps — p.155
  - Administering VM Apps Organizations in VCF Automation — p.367
  - Using the ServiceNow ITSM Plug-in for VCF Automation — p.402
- Workload Orchestration — p.443
  - Managing VMware Cloud Foundation Operations Orchestrator — p.443
  - Administering VCF Operations Orchestrator — p.446
  - Developing Workflows with VCF Operations Orchestrator — p.463
  - Using the VCF Operations orchestrator Plug-ins — p.517 (Active Directory, AMQP, Auto Deploy, HTTP-REST, Mail, Multi-Node, PowerShell, SNMP, SOAP, SQL, SSH, vCenter, vCloud Suite API, VCF Automation, XML plug-ins)
- Building Cloud Applications — p.604
- Private AI — p.818
- Administration SDKs, APIs, and CLI — p.819
  - VMware Cloud Foundation APIs and SDKs — p.819
    - OAuth Token Support for API and CLI Access — p.821
    - VMware Cloud Foundation API Sample Programs — p.829
    - Core vSphere APIs — p.831
    - Supplementary vSphere APIs — p.833
    - VKS (vSphere Kubernetes Service) Programming — p.837
    - vSphere Add-On SDKs — p.844
    - Tagging Examples Using vSphere APIs — p.844
    - Some Use Cases for VMware SDKs — p.863
  - VMware Cloud Foundation SDKs Developer's Setup Guide — p.865

## Part 10: VCF-9.1.1_Part10_AdminSDKs-APIs-CLI.pdf (935 pages)
Covers: VMware Cloud Foundation Programming Guide, VCF PowerCLI, VCF Operations API
Page numbers (p.N) are local to this file.

- Samples for SDDC Manager — p.1
- VMware Cloud Foundation Programming Guide — p.1
  - Introduction to the VMware Cloud Foundation REST API — p.1
  - Introduction to the VMware Cloud Foundation SDKs — p.190
  - The vSphere Web Services API — p.373
  - Using the vSAN Management APIs — p.647
  - How to Develop vSphere Solution — p.690
  - VMware Storage Policies — p.733
  - vCenter Single Sign-On Client Example — p.754
  - Remote Serial Port Access with a Virtual Serial Port Proxy — p.764
- VMware Cloud Foundation PowerCLI — p.779
  - Compatibility Matrix — p.779
  - Microsoft PowerShell Basics — p.782
  - VCF PowerCLI Concepts — p.783
  - Installing VMware Cloud Foundation PowerCLI — p.788
  - Configuring VMware Cloud Foundation PowerCLI — p.791
  - Managing vSphere with VCF PowerCLI — p.797
  - Managing the VCF API with VCF PowerCLI — p.875
  - Managing VMware vSAN with VCF PowerCLI — p.879
  - Managing vSphere Replication API with VCF PowerCLI — p.885
  - Managing VMware Live Site Recovery with VCF PowerCLI — p.890
  - Managing the NSX Policy API with VCF PowerCLI — p.900
  - Managing VMware Cloud Director with VCF PowerCLI — p.904
  - Managing VCF Operations with VCF PowerCLI — p.912
  - Managing VMware Cloud on AWS with VCF PowerCLI — p.914
  - Generate a VCF PowerCLI Support Bundle — p.917
- Understanding the VMware Cloud Foundation Operations API — p.917
  - How the API Works / Client Workflow Overview — p.918
  - Getting Started with the API — p.922
  - Configuring an Adapter Instance — p.926

## Part 11: VCF-9.1.1_Part11_AdvancedServices-Index.pdf (294 pages)
Covers: VCF Operations for Networks API Guide, VCF Automation APIs, Advanced Services, Index
Page numbers (p.N) are local to this file.

- Start Monitoring the New Adapter Instance — p.1
- VMware Cloud Foundation Operations for Networks API Guide — p.1
  - Understanding the REST APIs — p.2
  - Managing Data Sources — p.14
  - Tagging IP Addresses — p.22
  - Performing Search — p.23
  - Working with Entities — p.31
  - Creating Applications and Tiers — p.37
  - Working with Streaming Databus — p.39
  - Generating the Recommended Firewall Rules — p.40
  - Fetching Metrics — p.44
  - Get Proxy Node Details / Version Info — p.46
- VCF Automation and APIs — p.47
  - About VCF Automation Applications — p.47
  - APIs for Service Provider Management — p.49
  - APIs for All Apps Organization Management — p.61
  - APIs for VM Apps Organization Management — p.69
    - VCF Automation Tutorials — p.82
    - Setting up VCF Automation using APIs — p.143
    - Using VCF Automation APIs to Build your Resource Infrastructure — p.169
    - Managing Your Projects — p.208
    - Working with Blueprints/Cloud Templates — p.213
    - Requesting a Deployment from a Catalog Item — p.252
    - Working with Deployments and Resources — p.259
  - Help and Support for VCF SDKs, APIs, and VCF PowerCLI — p.289
- Advanced Services — p.291
- Documentation Legal Notice — p.293
