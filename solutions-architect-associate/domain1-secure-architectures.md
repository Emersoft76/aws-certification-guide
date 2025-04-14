# 🔐 Domain 1: Design Secure Architectures | Projetar Arquiteturas Seguras

> 🇬🇧 This section covers the key principles of security, identity, and compliance for AWS architecture.  
> 🇧🇷 Esta seção cobre os principais princípios de segurança, identidade e conformidade para arquiteturas AWS.

---

## ✅ 1.1 – Secure Access to AWS Resources | Acesso Seguro aos Recursos da AWS

### 🇬🇧
- Use **IAM roles** instead of access keys.
- Implement **MFA** for privileged users.
- Apply **least privilege** principle in policies.

### 🇧🇷
- Use **funções IAM** em vez de chaves de acesso.
- Implemente **MFA** para usuários privilegiados.
- Aplique o princípio de **menor privilégio** nas políticas.

---

## ✅ 1.2 – Secure Application Tiers | Camadas de Aplicações Seguras

### 🇬🇧
- Use **security groups** to control EC2 traffic.
- Isolate databases in **private subnets**.
- Encrypt data **in transit** and **at rest** using AWS KMS and SSL.

### 🇧🇷
- Use **grupos de segurança** para controlar o tráfego em EC2.
- Isole bancos de dados em **subnets privadas**.
- Criptografe dados **em trânsito** e **em repouso** com AWS KMS e SSL.

---

## ✅ 1.3 – Data Protection and Encryption | Proteção e Criptografia de Dados

### 🇬🇧
- **KMS** for managing encryption keys.
- **S3 bucket policies** + **block public access**.
- **CloudTrail** for audit logging.

### 🇧🇷
- **KMS** para gerenciar chaves de criptografia.
- **Políticas de bucket S3** + **bloqueio de acesso público**.
- **CloudTrail** para registros de auditoria.

---

## ✅ 1.4 – Identity Federation & Single Sign-On

### 🇬🇧
- Integrate IAM with **SAML or Active Directory**.
- Use **AWS SSO** for centralized identity control.

### 🇧🇷
- Integre o IAM com **SAML ou Active Directory**.
- Use **AWS SSO** para controle de identidade centralizado.

---

> 🔗 Next Domain: [Resilient Architectures](./domain2-resilient-architectures.md)
