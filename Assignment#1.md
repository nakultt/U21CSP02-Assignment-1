# Assignment 1 Submissions

# 1 Poster Presentation + Linkedin
> Enter the Linkedin Post URL
> [\[Linkedin URL here\]](https://www.linkedin.com/posts/nakult_dataengineering-dataanalysis-learningjourney-activity-7431274791094894592-YsHL?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFKf9voBAd-FVSRSLEAiS1qQo6rP_5rXKwA) : https://www.linkedin.com/posts/nakult_dataengineering-dataanalysis-learningjourney-activity-7431274791094894592-YsHL?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFKf9voBAd-FVSRSLEAiS1qQo6rP_5rXKwA

> Poster Link :
> https://drive.google.com/file/d/1Db_3C-1zncBBXyUmCOPZdCzhVBcv84QC/view?usp=sharing

# 2 GitHub Students Developers Pack
> Enter the GitHub Students Developers Pack Screenshot
> [\[GitHub Students Developers Pack Screenshot\]](https://drive.google.com/file/d/199My0uT2R77m0UxNBzyVm67OoHT8BdsY/view?usp=drive_link) : https://drive.google.com/file/d/199My0uT2R77m0UxNBzyVm67OoHT8BdsY/view?usp=drive_link

> LinkedIn: https://www.linkedin.com/posts/nakult_github-studentdeveloperpack-learningjourney-activity-7431279578133798912-R2Ez?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFKf9voBAd-FVSRSLEAiS1qQo6rP_5rXKwA

# 3 AI-Assisted Note Creation using NotebookLM - Unit 1 Topics
> [Enter the NotebookLM URL](https://notebooklm.google.com/notebook/82680743-ee6a-45c3-956a-b1aed979eb9e) : https://notebooklm.google.com/notebook/82680743-ee6a-45c3-956a-b1aed979eb9e

> Material url: https://docs.google.com/document/d/1RPje-eKLsOZFENRSPwXJwh-4eMwiUZGWmSJ_vUIHh0A/edit?usp=sharing

# 4 AI-Assisted Note Creation using Claude (Artifacts) - Unit 2 Topics
> Chat Link : https://claude.ai/share/88e4f7c1-fd92-4455-bf82-4dd665809741

> Enter the Claude (Artifacts) URL : https://drive.google.com/file/d/1q_mhdS3mh0dyYqMAZvKHYAyvb_wde7Ss/view?usp=sharing

# 5 AI-Assisted Note Creation using ChatGPT (Canvas) - Unit 3 Topic
> Chat Link : https://chatgpt.com/share/699af7aa-669c-8011-99e4-5e9d707b76b7

> Create a file question5.md and enter the content there

# Virtual, Physical, and Cloud Data Protection

## Introduction
Data protection ensures that information remains **confidential, available, and recoverable** in case of hardware failure, cyberattacks, human error, or disasters. 

Storage and protection strategies differ significantly across:
- **Physical (On-Premise) Environments**
- **Virtualized Environments**
- **Cloud Environments**

Understanding these architectural differences is essential for designing resilient storage systems.

---

# 1. Physical (Traditional / On-Premise) Data Protection

## 1.1 How Data is Stored
- Stored on **dedicated physical servers** in local data centers.
- Uses HDDs, SSDs, RAID arrays.
- Storage types:
  - Direct Attached Storage (DAS)
  - Network Attached Storage (NAS)
  - Storage Area Network (SAN)
- Applications typically run on **separate dedicated hardware**.

## 1.2 Data Protection Strategies

### A. Hardware-Level Protection
- **RAID 1** – Disk mirroring
- **RAID 5** – Parity-based protection
- **RAID 6** – Double parity
- **RAID 10** – Striping + Mirroring
- Protects against **disk failure only** (not corruption or ransomware)

### B. Backup Mechanisms
- Full backups
- Incremental backups
- Differential backups
- Tape backups (offline / air-gapped storage)
- Scheduled backup windows

### C. Security Strategies
- Physical isolation of servers
- Restricted data center access
- Perimeter firewall protection
- Network segmentation
- Antivirus and endpoint protection
- Role-based access control (RBAC)

### D. Disaster Recovery (DR)
- Secondary site replication
- Cold site / Warm site / Hot site setups
- Manual failover procedures

## 1.3 Advantages
- Full hardware control
- Predictable performance
- Easier compliance in some industries

## 1.4 Limitations
- High capital expenditure (CapEx)
- Limited scalability
- Manual recovery processes
- Requires physical maintenance

---

# 2. Virtual Data Protection

## 2.1 How Data is Stored
- Physical hardware runs multiple **Virtual Machines (VMs)**.
- Managed by a **hypervisor**.
- Data stored as virtual disk files (e.g., VMDK, VHD).
- Shared storage across multiple VMs.
- Better resource utilization than physical-only setups.

## 2.2 Data Protection Strategies

### A. Snapshot Technology
- VM snapshots capture:
  - Disk state
  - Memory state
  - System configuration
- Enables quick rollback to a previous state
- Useful for testing and short-term recovery
- Not a replacement for backups

### B. VM-Level Backup
- Image-based VM backups
- Agentless backups using hypervisor APIs
- Application-aware backups

### C. Replication & High Availability
- VM replication to another host
- Automatic VM restart if host fails
- Live migration between hosts
- Cluster-based failover systems

### D. Security Strategies
- Hypervisor-level isolation
- VM segmentation
- Virtual firewalls
- Snapshot-based ransomware recovery
- Access control at VM and management layer
- Monitoring via centralized logging systems

## 2.3 Advantages
- Improved Recovery Time Objective (RTO)
- Efficient hardware usage
- Easier system migration
- Faster provisioning

## 2.4 Limitations
- Shared resource risks (noisy neighbor problem)
- Hypervisor is a single point of dependency
- Snapshot misuse may degrade performance

---

# 3. Cloud Data Protection

## 3.1 How Data is Stored
- Data stored in **distributed cloud data centers**.
- Software-defined storage architecture.
- Storage types:
  - Object storage
  - Block storage
  - File storage
- Multi-tenant architecture.
- Elastic scaling capabilities.

## 3.2 Data Protection Strategies

### A. Built-in Redundancy
- Multi-Availability Zone replication
- Cross-region replication
- Erasure coding
- Automated failover systems

### B. Backup & Recovery
- Automated backups
- Point-in-Time Recovery (PITR)
- Continuous data protection
- Versioning for objects
- Object lock (immutability)

### C. Security Strategies
- Encryption at rest
- Encryption in transit (TLS)
- Identity and Access Management (IAM)
- Multi-Factor Authentication (MFA)
- Zero-trust security model
- Security monitoring & threat detection services

### D. Disaster Recovery
- Geo-redundancy across regions
- Instant scaling during failure
- Managed disaster recovery services

## 3.3 Advantages
- High scalability (elastic)
- Operational expenditure (OpEx) model
- Built-in high availability
- Global accessibility
- Automated recovery processes

## 3.4 Limitations
- Vendor lock-in risk
- Internet dependency
- Compliance and data residency concerns
- Less physical control

---

# 4. Key Differences Summary

## 4.1 Infrastructure Model
- **Physical** → Dedicated hardware
- **Virtual** → Software abstraction over shared hardware
- **Cloud** → Provider-managed distributed infrastructure

## 4.2 Protection Mechanism Focus
- **Physical** → RAID + Backup + Physical isolation
- **Virtual** → Snapshots + VM replication + Hypervisor isolation
- **Cloud** → Redundancy + Automation + Geo-replication + IAM

## 4.3 Scalability
- Physical → Hardware-limited
- Virtual → Moderately scalable
- Cloud → Highly elastic and on-demand

## 4.4 Recovery Speed
- Physical → Manual restoration (slow)
- Virtual → VM-level restore (faster)
- Cloud → Automated failover (very fast)

## 4.5 Cost Model
- Physical → Capital Expenditure (CapEx)
- Virtual → Optimized CapEx
- Cloud → Operational Expenditure (OpEx)

---

# 5. Core Concept Comparison Table

| Feature | Physical | Virtual | Cloud |
|----------|-----------|-----------|-----------|
| Infrastructure | Dedicated hardware | Hypervisor-based | Distributed provider-managed |
| Redundancy | RAID | VM replication | Multi-zone & multi-region |
| Backup | Disk/Tape | Image-based VM backup | Managed automated backup |
| Security Model | Perimeter-based | Hypervisor + Network | Shared responsibility |
| Scalability | Limited | Moderate | Elastic |
| Recovery | Manual | VM restore | Automated failover |

---

# 6. Exam Quick Revision Points

- RAID protects against disk failure, not corruption.
- Snapshots are not long-term backups.
- Virtualization improves RTO.
- Cloud uses distributed redundancy and automation.
- Cloud follows a shared responsibility model.

---

# Conclusion

Data protection evolves from **hardware-centric (Physical)** to **software-abstracted (Virtual)** and finally to **fully distributed and automated (Cloud)** architectures.

Each environment introduces improved scalability and recovery capabilities but also new security responsibilities. A strong understanding of these differences is essential for designing modern storage systems.



# 6 Secure File Upload to AWS S3 using Pre-Signed URL
> https://drive.google.com/file/d/1YrQvs-iztbn-iaERKQpmjM29V5bdQ9bw/view?usp=sharing

>https://drive.google.com/file/d/15q4g2jlAihAUD00XEcZIoUaQKtJ14Dkp/view?usp=sharing