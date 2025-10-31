# ☁️ Gerenciamento de Instâncias EC2 e AMIs  
### Usando o **AWS Toolkit for Visual Studio**

![AWS Toolkit](https://img.shields.io/badge/AWS-Toolkit-orange?logo=amazonaws)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-IDE-purple?logo=visualstudio)
![EC2](https://img.shields.io/badge/EC2-Compute-blue?logo=amazonec2)
![Status](https://img.shields.io/badge/Status-Ativo-success)

---

## 🧭 Visão Geral  
O **AWS Toolkit for Visual Studio** permite visualizar, iniciar, conectar, interromper ou encerrar instâncias **EC2** e gerenciar **AMIs (Amazon Machine Images)** — tudo direto do Visual Studio.  
📘 [Documentação oficial (pt-br)](https://docs.aws.amazon.com/pt_br/toolkit-for-visual-studio/latest/user-guide/tkv-ec2-ami.html)

---

## ⚙️ Funcionalidades Principais

### 🖥️ Visualizar Instâncias e AMIs  
- Acesse o **AWS Explorer → Amazon EC2 → Instâncias / AMIs**.  
- Liste, atualize e ordene instâncias por região.  

### 🔐 Conectar-se a uma Instância (Windows)  
- Clique com o botão direito → **Open Remote Desktop**.  
- Faça login via par de chaves ou senha do administrador obtida pelo Toolkit.  

### 🛑 Parar ou Encerrar Instâncias  
- **Stop:** mantém o volume EBS (armazenamento persistente).  
- **Terminate:** encerra totalmente a instância e apaga o armazenamento local.  

### 📸 Criar uma AMI a partir de uma Instância  
- Clique com o botão direito → **Create Image (AMI)**.  
- Dê nome e descrição; verifique o resultado em *AMIs*.  

---

## 🧩 Quando Usar  
✅ Clonar ambientes pré-configurados.  
✅ Criar imagens de referência para desenvolvimento.  
✅ Reduzir custos encerrando instâncias não usadas.  

---

## ⚠️ Atenção  
- Instâncias **paradas** ainda geram custo de **EBS**.  
- As ações do Toolkit dependem da **região AWS** selecionada.  

---

### 🔗 Referência  
📚 [AWS Docs – Gerenciando Instâncias e AMIs no Visual Studio](https://docs.aws.amazon.com/pt_br/toolkit-for-visual-studio/latest/user-guide/tkv-ec2-ami.html)

---

> 💡 **Dica:**  
> Quer deixar o README ainda mais bonito?  
> Você pode adicionar imagens de tela (screenshots) do Visual Studio com o Toolkit.  
> Exemplo:
> ```markdown
> ![Exemplo AWS Explorer](./img/aws-explorer.png)
> ```

---

### ✨ Autor
Desenvolvido por *[seu-nome]* — Projeto de estudo AWS EC2.

