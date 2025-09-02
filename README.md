# Configuração de uma Instância de Banco de Dados no Microsoft Azure

Este documento descreve, passo a passo, como configurar uma instância de banco de dados **Azure SQL Database**, utilizando o portal do Microsoft Azure. Ideal para ambientes de desenvolvimento, testes ou produção.

---

## 📋 Índice

- [✅ Pré-requisitos](#-pré-requisitos)
- [⚙️ Etapas de Configuração](#️-etapas-de-configuração)
  - [1. Acesso ao Portal Azure](#1-acesso-ao-portal-azure)
  - [2. Criação do Resource Group](#2-criação-do-resource-group)
  - [3. Criação do Servidor SQL](#3-criação-do-servidor-sql)
  - [4. Criação do Banco de Dados](#4-criação-do-banco-de-dados)
  - [5. Configuração do Firewall](#5-configuração-do-firewall)
  - [6. Conexão ao Banco de Dados](#6-conexão-ao-banco-de-dados)
- [💡 Boas Práticas](#-boas-práticas)
- [🔗 Links Úteis](#-links-úteis)
- [👨‍💻 Autor](#-autor)

---

## ✅ Pré-requisitos

Antes de iniciar a configuração, você precisará de:

- Conta Microsoft com acesso ao [Azure Portal](https://portal.azure.com)
- Permissões para criar recursos na assinatura do Azure
- Ferramenta de conexão com banco de dados SQL, como:
  - Azure Data Studio
  - SQL Server Management Studio (SSMS)
  - DBeaver

---

## ⚙️ Etapas de Configuração

### 1. Acesso ao Portal Azure

Acesse o portal do Azure:
```bash
https://portal.azure.com
