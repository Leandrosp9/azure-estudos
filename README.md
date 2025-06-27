# ☁️ Desafio DIO - Gerenciamento de Máquinas Virtuais no Azure

Este repositório foi criado como parte do **desafio prático da DIO** para a formação em **Microsoft - Azure Administrator Certification (AZ-104)**. Ele documenta de forma estruturada a criação de uma máquina virtual no Azure, aplicando os conhecimentos aprendidos nas aulas, com resumos e dicas úteis para futuras implementações.

---

## 🎯 Objetivo do Repositório

- Consolidar os conhecimentos adquiridos nas aulas da DIO com foco em máquinas virtuais.
- Demonstrar a aplicação prática desses conhecimentos na plataforma Microsoft Azure.
- Utilizar o **GitHub** como ferramenta de versionamento e documentação técnica.
- Servir como **material de apoio para estudos futuros** e consulta rápida.

---

## 🧪 Laboratório Prático – Criação de Máquina Virtual no Azure

### 📘 Descrição

Neste laboratório, foi criada uma VM com Windows Server 2019 Datacenter no portal do Azure, utilizando boas práticas de organização, nomenclatura e segurança.

---

## 🧾 Resumo da Configuração da VM

### 🔹 Informações Gerais

| Item                        | Valor                        |
|-----------------------------|------------------------------|
| Assinatura                  | Azure subscription 1         |
| Grupo de Recursos           | az-104-rg                    |
| Nome da VM                  | az-104-01                    |
| Região                      | East US                      |
| Imagem                      | Windows Server 2019 Gen2     |
| Arquitetura                 | x64                          |
| Tamanho                     | Standard B1s (1 vCPU, 1 GiB RAM) |
| Licença                     | Azure (sem licença própria)  |
| Redundância / Zona          | Nenhuma / Auto-selecionada   |
| Azure Spot                  | Não                          |
| Hibernação                  | Desabilitada                 |

---

### 💾 Disco e Rede

| Item                    | Valor                           |
|-------------------------|---------------------------------|
| Tipo de Disco           | SSD Standard (LRS)              |
| VNet/Sub-rede           | az-104-01-vnet / default        |
| IP Público              | az-104-01-ip                    |
| Portas Públicas         | Nenhuma                         |
| NIC/IP/Disk deletáveis  | Sim (quando a VM for removida)  |

---

### 🔧 Gerenciamento e Monitoramento

| Recurso                        | Configuração         |
|--------------------------------|----------------------|
| Backup                         | Desabilitado         |
| Diagnóstico de Inicialização  | Ativado              |
| Diagnóstico de Convidado       | Desativado           |
| Microsoft Defender             | Básico (gratuito)    |
| Identidade Gerenciada (MSI)    | Desativado           |
| Login com Entra ID             | Desativado           |

---

### 👤 Conta Administrador

| Item             | Valor    |
|------------------|----------|
| Nome de usuário  | `gdo`    |
| Senha            | (segura e não exposta) |
| Acesso público   | Não permitido inicialmente |

---

## 📎 Estrutura do Repositório

```
azure-estudos/
├── labs/
│   └── lab-01-criacao-vm.md   # Resumo técnico do laboratório
├── imagens/
│   └── vm-azure-portal.png    # Captura de tela da VM criada (opcional)
├── scripts/
│   └── criar-vm-cli.sh        # Script CLI para automatizar (opcional)
├── README.md                  # Este arquivo
```

---

## ✅ Habilidades Demonstradas

- Provisão de máquinas virtuais no Azure via Portal.
- Documentação técnica clara e padronizada.
- Uso do GitHub para versionamento e organização.
- Aplicação de boas práticas de segurança e organização de recursos.

---

## 🧠 Aprendizados

- O provisionamento manual ajuda a compreender cada etapa da criação de recursos.
- O uso adequado de nomes e grupos facilita o gerenciamento em escala.
- Desativar recursos não utilizados evita cobranças e melhora a segurança.
- O GitHub pode ser uma excelente base para um **portfólio técnico profissional**.

---

## 📚 Recursos Úteis

- [Portal do Azure](https://portal.azure.com/)
- [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- [DIO - Formação Azure Administrator](https://web.dio.me/)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

---

> Desafio concluído com base nos requisitos propostos pela DIO 🚀