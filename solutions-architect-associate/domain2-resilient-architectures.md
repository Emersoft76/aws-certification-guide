# ♻️ Domain 2: Design Resilient Architectures | Projetar Arquiteturas Resilientes

> 🇬🇧 This domain covers designing systems that are highly available, fault-tolerant, and capable of disaster recovery.  
> 🇧🇷 Este domínio aborda o design de sistemas altamente disponíveis, tolerantes a falhas e com capacidade de recuperação de desastres.

---

## ✅ 2.1 – High Availability | Alta Disponibilidade

### 🇬🇧
- Use **multiple Availability Zones** for redundancy.
- Deploy applications behind **Load Balancers**.
- Use **Auto Scaling Groups (ASG)** to maintain healthy capacity.

### 🇧🇷
- Use **múltiplas Zonas de Disponibilidade** para redundância.
- Implemente aplicações atrás de **Load Balancers**.
- Use **Grupos de Auto Scaling (ASG)** para manter a capacidade saudável.

---

## ✅ 2.2 – Fault Tolerance | Tolerância a Falhas

### 🇬🇧
- Replicate data across **AZs or Regions**.
- Design **stateless** application tiers.
- Implement **retry logic and exponential backoff** in apps.

### 🇧🇷
- Replique dados entre **Zonas de Disponibilidade ou Regiões**.
- Projete camadas de aplicação **sem estado**.
- Implemente **lógica de repetição com backoff exponencial** nos aplicativos.

---

## ✅ 2.3 – Disaster Recovery | Recuperação de Desastres

### 🇬🇧
- DR Strategies: **Backup & Restore**, **Pilot Light**, **Warm Standby**, **Multi-Site**.
- Use services like **AWS Backup**, **S3 Cross-Region Replication**, and **RDS Multi-AZ**.

### 🇧🇷
- Estratégias de DR: **Backup & Restore**, **Pilot Light**, **Warm Standby**, **Multi-Site**.
- Use serviços como **AWS Backup**, **Replicação entre Regiões do S3** e **RDS Multi-AZ**.

---

## ✅ 2.4 – Elasticity and Scalability

### 🇬🇧
- Use **Auto Scaling** and **Elastic Load Balancing** for elastic compute.
- Design **loosely coupled** and **event-driven** architectures (e.g., SQS + Lambda).

### 🇧🇷
- Use **Auto Scaling** e **Elastic Load Balancing** para elasticidade computacional.
- Projete arquiteturas **pouco acopladas** e **orientadas a eventos** (ex: SQS + Lambda).

---

> 🔗 Next Domain: [High-Performing Architectures](./domain3-high-performing-architectures.md)
