# 🚀 Fix Teams Full Automation

Script completo para correção automática do Microsoft Teams em ambientes corporativos, com suporte a execução local, remota e via domínio.

---

## 🧠 Visão Geral

Este projeto resolve problemas comuns do Microsoft Teams como:

* ❌ Installation has failed
* ❌ Falhas no AppX / Microsoft Store
* ❌ Resquícios de instalações antigas

👉 Tudo isso de forma automatizada e escalável.

---

## ⚙️ Funcionalidades

* Limpeza completa do Teams (arquivos + registro)
* Correção do Microsoft Store / AppX
* Reparo do Windows (DISM + SFC)
* Instalação automática do WebView2
* Instalação do novo Microsoft Teams
* Geração de logs para auditoria (C:\Temp)

---

## 📂 Estrutura

```
.
├── Fix-Teams-Full.ps1
├── Run-FixTeams-Advanced.bat
└── README.md
```

---

## ▶️ Como usar

### 🔹 Execução Local

1. Execute o `.bat` como administrador
2. Escolha a opção **1 - Local**

---

### 🔹 Execução Remota

1. Escolha opção **2**
2. Informe os nomes dos computadores

---

### 🔹 Execução via Domínio

1. Escolha opção **3**
2. O script buscará máquinas automaticamente no AD

---

## ⚠️ Pré-requisitos

* Permissão de administrador
* PowerShell Remoting habilitado:

```powershell
Enable-PSRemoting -Force
```

* Script disponível em:

```
C:\Temp\Fix-Teams-Full.ps1
```

---

## 📊 Benefícios

* Redução de chamados repetitivos
* Padronização de suporte
* Execução em massa
* Pronto para ambientes corporativos

---

## 🔥 Roadmap

* [ ] Integração com Intune / SCCM
* [ ] Dashboard com Power BI
* [ ] Log centralizado

---

## 👨‍💻 Autor

Projeto voltado para automação de infraestrutura e suporte corporativo.

---

## 📌 Licença

Uso livre para estudos e ambientes corporativos.
