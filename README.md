# 🌿 Millennium Farma - Implementação de Serviços AWS

> Projeto de adoção de tecnologias AWS para automação, segurança e escalabilidade na distribuição de medicamentos.

---

## 📅 Data
**24/08/2025**

## 👤 Responsável
**Ivan Barbosa**

## 🎯 Objetivo
Implementar soluções AWS para a Millennium Farma, com foco em:

- 💰 Redução de custos operacionais  
- ⚡ Automação de processos  
- 🔒 Segurança e confiabilidade dos dados  
- 📈 Escalabilidade de infraestrutura  

---

## ⚙️ Tecnologias AWS Utilizadas

| Serviço | Foco | Caso de Uso | Status |
|--------|------|------------|--------|
| **[Amazon S3](https://aws.amazon.com/s3/)** | Armazenamento de dados | Guardar registros de estoque, notas fiscais e pedidos | ![S3 Status](https://github.com/usuario/millennium-farma/actions/workflows/s3.yml/badge.svg) |
| **[Amazon RDS](https://aws.amazon.com/rds/)** | Banco de dados gerenciado | Gerenciar clientes, farmácias e inventário | ![RDS Status](https://github.com/usuario/millennium-farma/actions/workflows/rds.yml/badge.svg) |
| **[AWS Lambda](https://aws.amazon.com/lambda/)** | Processamento serverless | Automatizar notificações e integrações | ![Lambda Status](https://github.com/usuario/millennium-farma/actions/workflows/lambda.yml/badge.svg) |
| **[Amazon CloudWatch](https://aws.amazon.com/cloudwatch/)** | Monitoramento | Coletar métricas, gerar logs e alertas | ![CloudWatch Status](https://github.com/usuario/millennium-farma/actions/workflows/cloudwatch.yml/badge.svg) |
| **[AWS IAM](https://aws.amazon.com/iam/)** | Segurança | Gerenciar acessos e permissões | ![IAM Status](https://github.com/usuario/millennium-farma/actions/workflows/iam.yml/badge.svg) |

> ⚡ **Observação:** Os badges acima são dinâmicos e atualizam automaticamente o status das implementações via GitHub Actions.

---

## 🏗 Arquitetura do Projeto

```text
   [Farmácias Parceiras] 🌐
            │
            ▼
      [AWS Lambda] ⚡  ← Automatização de processos
            │
            ▼
 [Amazon S3] 🗂 ← Armazena documentos, logs, notas fiscais
            │
            ▼
 [Amazon RDS] 🗄 ← Banco de dados centralizado
            │
            ▼
 [CloudWatch] 📊 ← Monitoramento e alertas
            │
            ▼
 [IAM] 🔒 ← Gerencia acessos e segurança

```


---

## ✅ Benefícios Esperados

* 🔄 Processos automatizados e integrados
* 🚀 Maior eficiência e produtividade
* 💸 Redução de custos com infraestrutura
* 🛡️ Segurança reforçada e compliance
* 📈 Escalabilidade pronta para crescimento futuro

---

## 🗺 Roadmap de Evolução

| Objetivo                                                  | Status                                                                                                       | Prazo Estimado |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | -------------- |
| Implementar notificações automáticas de pedidos           | ![S3 Status](https://github.com/usuario/millennium-farma/actions/workflows/s3.yml/badge.svg)                 | 30/09/2025     |
| Automatizar integração com fornecedores                   | ![Lambda Status](https://github.com/usuario/millennium-farma/actions/workflows/lambda.yml/badge.svg)         | 31/10/2025     |
| Adotar AWS CloudFormation para infraestrutura como código | ![RDS Status](https://github.com/usuario/millennium-farma/actions/workflows/rds.yml/badge.svg)               | 15/11/2025     |
| Criar dashboards interativos de métricas                  | ![CloudWatch Status](https://github.com/usuario/millennium-farma/actions/workflows/cloudwatch.yml/badge.svg) | 30/11/2025     |

---

## 📎 Anexos

* 📝 [Relatório completo de implementação](docs/relatorio_final.pdf)
* 📚 Guias e manuais de cada serviço AWS
* 📊 Planilhas de controle de estoque e pedidos

---

### 🔗 Links Úteis

* [AWS Console](https://aws.amazon.com/console/)
* [Documentação S3](https://docs.aws.amazon.com/s3/index.html)
* [Documentação RDS](https://docs.aws.amazon.com/rds/index.html)
* [Documentação Lambda](https://docs.aws.amazon.com/lambda/index.html)
* [Documentação CloudWatch](https://docs.aws.amazon.com/cloudwatch/index.html)
* [Documentação IAM](https://docs.aws.amazon.com/iam/index.html)



### ✅ Recursos desta versão “dashboard interativo”:
- **Badges dinâmicos** que refletem status atual do GitHub Actions.  
- **Seção Roadmap** com badges vinculados às tarefas específicas.  
- **Mini-diagrama de arquitetura** para visualização rápida.  
- **Links diretos para AWS e documentação oficial**.  
- Estrutura clara e enxuta, mantendo visual moderno.
