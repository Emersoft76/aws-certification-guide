# 💸 Domain 4: Design Cost-Optimized Architectures | Projetar Arquiteturas Otimizadas para Custo

> 🇬🇧 This domain focuses on cost-effective resource management in AWS environments.  
> 🇧🇷 Este domínio foca na gestão eficiente de custos em ambientes AWS.

---

## ✅ 4.1 – Cost-Effective Compute

### 🇬🇧
- Use **Spot Instances** for stateless, flexible, and fault-tolerant workloads.
- Use **Savings Plans** or **Reserved Instances** for steady workloads.
- Use **Auto Scaling** to avoid overprovisioning.

### 🇧🇷
- Use **Instâncias Spot** para cargas de trabalho sem estado, flexíveis e tolerantes a falhas.
- Use **Savings Plans** ou **Instâncias Reservadas** para cargas constantes.
- Use **Auto Scaling** para evitar superdimensionamento.

---

## ✅ 4.2 – Cost-Effective Storage

### 🇬🇧
- Use **S3 Lifecycle Policies** to move infrequently accessed data to cheaper storage (Glacier).
- Use **Intelligent-Tiering** for dynamic access pattern optimization.
- Avoid storing logs in high-IOPS EBS.

### 🇧🇷
- Use **políticas de ciclo de vida no S3** para mover dados acessados com pouca frequência para camadas mais baratas (Glacier).
- Use **Intelligent-Tiering** para otimização dinâmica do padrão de acesso.
- Evite armazenar logs em volumes EBS com IOPS elevado.

---

## ✅ 4.3 – Cost-Effective Databases

### 🇬🇧
- Use **Aurora Serverless** for variable workloads.
- Use **RDS Reserved Instances** for consistent use.
- Use **DynamoDB On-Demand** for unpredictable traffic.

### 🇧🇷
- Use **Aurora Serverless** para cargas variáveis.
- Use **Instâncias Reservadas RDS** para uso constante.
- Use **DynamoDB On-Demand** para tráfego imprevisível.

---

## ✅ 4.4 – Cost Visibility and Monitoring

### 🇬🇧
- Enable **AWS Budgets** and **Cost Explorer**.
- Use **Resource Tags** for better cost attribution.
- Monitor with **CloudWatch metrics** to right-size resources.

### 🇧🇷
- Ative o **AWS Budgets** e o **Cost Explorer**.
- Use **Tags de Recursos** para melhor atribuição de custos.
- Monitore com **CloudWatch** para ajustar corretamente os recursos.

---

> 🔗 Next: [questions-single-answer.md](./questions-single-answer.md)
