# 🌀 Implementando sua primeira stack com AWS Cloud Formation  

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![CloudFormation](https://img.shields.io/badge/CloudFormation-Infrastructure%20as%20Code-blue?logo=amazonaws)
![Status](https://img.shields.io/badge/Status-Ativo-success)
![Tipo](https://img.shields.io/badge/Tipo-Automação-lightgrey)

---

## ⚙️ O que é o AWS CloudFormation e Stack?  

O **AWS CloudFormation** é um serviço que permite **modelar, provisionar e gerenciar recursos da AWS de forma automatizada**.   

Uma **Stack** é um conjunto de recursos AWS (como instâncias EC2, buckets S3, bancos RDS, funções Lambda etc.) que são criados com base em um templates (em YAMLS ou JSON), num único arquivo da **AWS CloudFormation**, representando uma implementação específica do seu modelo de infraestrutura

| Benefício                | Descrição                                                             |
| ------------------------ | --------------------------------------------------------------------- |
|  **Organização**         | Agrupa todos os recursos relacionados em uma unidade lógica.          |
|  **Gerenciamento fácil** | Atualiza, monitora ou exclue tudo de uma vez.                         |
|  **Reprodutibilidade**   | Permite replicar várias vezes  um ambiente (ex: dev, qa, prod).       |
|  **Controle de versão**  | Facilita rollback e histórico de mudanças.                            |


---
🧩 **Exemplo prático**

```text
Resources:
  MeuBucket:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: S3CloudFormation

```
Ao criar esse template no CloudFormation, será criada uma stack e dentro dela o recurso S3 Bucket. 

----

## 🌩️ Conclusão

As stacks são o uma facilidade da automação de infraestrutura como código (IaC) na AWS, visto que elas trazem organização, automação e consistência ao gerenciamento de infraestrutura na nuvem, o que torna o AWS CloudFormation uma ferramenta importante e de grande utilidade no gerenciamento das stacks.

