<div align="center">

# `GUILHERME DIAS`

### CYBERSECURITY ANALYST

**Blue Team · SOC · Security Investigation**

<br>

`INVESTIGO.` `ANALISO.` `APRENDO.` `DOCUMENTO.`

<br>

[![GitHub](https://img.shields.io/badge/GitHub-guilhermedias--cyber-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/guilhermedias-cyber)
[![Cybersecurity](https://img.shields.io/badge/CYBERSECURITY-00A8FF?style=for-the-badge&logo=hackthebox&logoColor=white)](#)
[![Blue Team](https://img.shields.io/badge/BLUE%20TEAM-00C2FF?style=for-the-badge&logo=shield&logoColor=white)](#)

</div>

---

<div align="center">

## `01 / SOBRE`

</div>

Profissional de **Cibersegurança** com experiência em ambientes corporativos, atuando com defesa cibernética, operações de segurança, análise de alertas, investigação de incidentes e proteção de dados.

Minha trajetória profissional começou em **infraestrutura e redes** e evoluiu para **Cybersecurity**, proporcionando uma visão ampla sobre ambientes Windows, redes, endpoints e controles de segurança.

Atualmente, concentro meus estudos e projetos em:

`SOC` · `Blue Team` · `Security Investigation` · `Threat Detection` · `Incident Response` · `DLP`

---

<div align="center">

## `02 / SECURITY OPERATIONS`

</div>

<table>
<tr>
<td width="50%">

### 🚨 SOC

**Security Operations Center**

- Alert Triage
- Log Analysis
- Incident Investigation
- Event Correlation

</td>

<td width="50%">

### 🛡️ BLUE TEAM

**Defensive Security**

- Threat Detection
- Incident Response
- Threat Hunting
- Security Monitoring

</td>
</tr>

<tr>
<td width="50%">

### 🔐 DLP

**Data Protection**

- Data Loss Prevention
- Policy Analysis
- Event Investigation
- Information Protection

</td>

<td width="50%">

### 🖥️ ENDPOINT

**Endpoint Security**

- EDR
- Windows Investigation
- Endpoint Telemetry
- Process Analysis

</td>
</tr>

<tr>
<td width="50%">

### 🌐 NETWORK

**Network Security**

- Traffic Analysis
- Network Investigation
- IOC Analysis
- Security Events

</td>

<td width="50%">

### 📋 FRAMEWORKS

**Security Methodologies**

- MITRE ATT&CK
- NIST
- Risk Analysis
- Security Investigation

</td>
</tr>
</table>

---

<div align="center">

## `03 / INVESTIGATION METHODOLOGY`

### Como eu transformo um alerta em uma conclusão de segurança

</div>

<table align="center">
<tr>
<td align="center">

**01**

<br>

🚨

<br>

`ALERTA`

</td>

<td align="center">→</td>

<td align="center">

**02**

<br>

🔎

<br>

`VALIDAÇÃO`

</td>

<td align="center">→</td>

<td align="center">

**03**

<br>

📊

<br>

`LOGS`

</td>

<td align="center">→</td>

<td align="center">

**04**

<br>

🧩

<br>

`COMPORTAMENTO`

</td>
</tr>

<tr>
<td align="center">

**05**

<br>

🌐

<br>

`THREAT INTELLIGENCE`

</td>

<td align="center">→</td>

<td align="center">

**06**

<br>

🖥️

<br>

`ENDPOINT`

</td>

<td align="center">→</td>

<td align="center">

**07**

<br>

⚠️

<br>

`IMPACTO`

</td>

<td align="center">→</td>

<td align="center">

**08**

<br>

🎯

<br>

`CLASSIFICAÇÃO`

</td>
</tr>
</table>

<br>

> **O objetivo não é apenas identificar um alerta.**
>
> É entender **o que aconteceu, quais evidências sustentam a hipótese e qual foi o impacto observado.**

---

<div align="center">

## `04 / FEATURED INVESTIGATION`

# 🔴 SQL INJECTION

### Let's Defend Lab #01

`WEB ATTACK` · `MITRE ATT&CK T1190` · `TRUE POSITIVE`

</div>

### Resumo

Investigação de um alerta relacionado a uma tentativa de **SQL Injection** contra um servidor web.

A análise envolveu:

- Validação do alerta
- Análise das requisições HTTP
- Análise do payload
- Correlação dos eventos
- Threat Intelligence
- Investigação do endpoint
- Avaliação do sucesso da exploração
- Classificação do incidente
- Documentação das evidências

### Resultado

| Indicador | Resultado |
|---|---|
| **Classificação** | 🟢 True Positive |
| **Tipo de ataque** | SQL Injection |
| **MITRE ATT&CK** | T1190 — Exploit Public-Facing Application |
| **Tráfego** | Internet → Company Network |
| **Ação do dispositivo** | Permitted |
| **Exploração bem-sucedida** | Não demonstrada |
| **Exfiltração** | Não observada |
| **Pós-exploração** | Não observada |
| **Escalonamento Tier 2** | Não |

### Evidências analisadas

```text
ALERTA
  ↓
REQUISIÇÕES HTTP
  ↓
PAYLOAD SQL INJECTION
  ↓
THREAT INTELLIGENCE
  ↓
ENDPOINT
  ↓
AVALIAÇÃO DA EXPLORAÇÃO
  ↓
CLASSIFICAÇÃO FINAL
