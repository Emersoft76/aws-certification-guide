# ⚡ Domain 3: Design High-Performing Architectures | Projetar Arquiteturas de Alto Desempenho

> 🇬🇧 This domain covers design principles to ensure performance in compute, storage, databases, and networking.  
> 🇧🇷 Este domínio cobre os princípios de design para garantir desempenho em computação, armazenamento, bancos de dados e redes.

---

## ✅ 3.1 – Choose High-Performance Compute Solutions

### 🇬🇧
- Use **EC2 instance types** based on workload (e.g., compute-optimized, memory-optimized).
- Use **Lambda** for short-lived, event-driven workloads.
- Use **Elastic Beanstalk** for managed deployment of apps.

### 🇧🇷
- Use **tipos de instâncias EC2** baseados na carga de trabalho (ex: otimizadas para computação, memória).
- Use **Lambda** para cargas de trabalho curtas e orientadas a eventos.
- Use **Elastic Beanstalk** para implantação gerenciada de aplicações.

---

## ✅ 3.2 – Optimize Storage Performance

### 🇬🇧
- Choose **EBS volume types** (e.g., gp3, io2) based on IOPS needs.
- Use **S3 Transfer Acceleration** for faster uploads.
- Use **Amazon FSx** for high-performance file systems.

### 🇧🇷
- Escolha os **tipos de volumes EBS** (ex: gp3, io2) de acordo com a necessidade de IOPS.
- Use o **S3 Transfer Acceleration** para uploads mais rápidos.
- Use o **Amazon FSx** para sistemas de arquivos de alto desempenho.

---

## ✅ 3.3 – Optimize Database Solutions

### 🇬🇧
- Use **RDS Read Replicas** to distribute read traffic.
- Use **DynamoDB DAX** for in-memory caching.
- Choose the right **database engine** based on workload.

### 🇧🇷
- Use **Read Replicas do RDS** para distribuir leitura.
- Use **DAX no DynamoDB** para cache in-memory.
- Escolha o **motor de banco de dados** adequado à carga de trabalho.

---

## ✅ 3.4 – Optimize Network Architecture

### 🇬🇧
- Use **CloudFront** to cache content globally.
- Use **VPC endpoints** for private access to AWS services.
- Use **Route 53 latency-based routing** for optimal DNS resolution.

### 🇧🇷
- Use o **CloudFront** para cache global de conteúdo.
- Use **endpoints de VPC** para acesso privado a serviços da AWS.
- Use o **Route 53 com roteamento baseado em latência** para resolver DNS de forma otimizada.

---

> 🔗 Next Domain: [Cost-Optimized Architectures](./domain4-cost-optimized-architectures.md)
