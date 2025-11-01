# 🌀 AWS Step Functions  

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![StepFunctions](https://img.shields.io/badge/Step%20Functions-Orquestra%C3%A7%C3%A3o%20de%20Servi%C3%A7os-blueviolet?logo=awslambda)
![Tipo](https://img.shields.io/badge/Tipo-Serverless-lightgrey)
![Status](https://img.shields.io/badge/Status-Ativo-success)

---

## ⚙️ O que é o AWS Step Functions?

O **AWS Step Functions** é um serviço da AWS que permite **orquestrar fluxos de trabalho** entre vários serviços AWS usando **máquinas de estado visuais**.  
Ele ajuda a coordenar **funções Lambda, tarefas EC2, ECS, DynamoDB, S3, SNS** e muitos outros serviços — tudo de forma **serverless**, com **monitoramento automático e reprocessamento de erros**.

---

## 🧩 Características Principais

- 🔁 **Orquestração Visual:** constrói fluxos de trabalho usando diagramas interativos.  
- ⚡ **Serverless:** sem necessidade de gerenciar servidores.  
- 🧠 **Tolerância a falhas:** reexecuta etapas automaticamente em caso de erro.  
- 📊 **Monitoramento Integrado:** acompanha a execução de cada etapa no Console AWS.  
- 🧱 **Integração Total:** funciona com Lambda, ECS, Glue, SageMaker, SQS, SNS e muito mais.  

---

## 💡 Exemplo de Utilização

Um fluxo simples para processar pedidos em um e-commerce pode usar o Step Functions assim:

1. **Receber pedido** (Lambda)
2. **Validar pagamento** (API Gateway + Lambda)
3. **Atualizar estoque** (DynamoDB)
4. **Enviar e-mail de confirmação** (SNS)

Representado visualmente:

```text
[Receber Pedido] 
       ↓
[Validar Pagamento]
       ↓
[Atualizar Estoque]
       ↓
[Enviar Confirmação]
