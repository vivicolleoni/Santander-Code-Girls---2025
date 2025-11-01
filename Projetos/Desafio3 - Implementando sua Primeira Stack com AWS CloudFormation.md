# 🌀 Implementando sua primeira stack com AWS Cloud Formation  

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![CloudFormation](https://img.shields.io/badge/CloudFormation-Infrastructure%20as%20Code-blue?logo=amazonaws)
![Status](https://img.shields.io/badge/Status-Ativo-success)
![Tipo](https://img.shields.io/badge/Tipo-Automação-lightgrey)

---

## ⚙️ O que é o AWS CloudFormation e Stack?  

O **AWS CloudFormation** é um serviço que permite **modelar, provisionar e gerenciar recursos da AWS de forma automatizada**.   

Uma **Stack** é um conjunto de recursos AWS (como instâncias EC2, buckets S3, bancos RDS, funções Lambda etc.) que são criados com base em um templates (em YAMLS ou JSON), num único arquivo da **AWS CloudFormation**, representando uma implementação específica do seu modelo de infraestrutura

| Benefício                  | Descrição                                                             |
| -------------------------- | --------------------------------------------------------------------- |
| 💡 **Organização**         | Agrupa todos os recursos relacionados em uma unidade lógica.          |
| 🔄 **Gerenciamento fácil** | Atualize, monitore ou exclua tudo de uma vez.                         |
| 🧱 **Reprodutibilidade**   | Permite criar o mesmo ambiente várias vezes (ex: dev, staging, prod). |
| 🧠 **Controle de versão**  | Facilita rollback e histórico de mudanças.                            |
