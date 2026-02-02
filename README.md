# Atualização do Projeto EyeWeb
## [ PORTUGUÊS - PT ]

<div align="center">

# EYEWEB REBORN

**PROJETO FINAL DE CIBERSEGURANÇA | 2º ANO CTESP**
*ISTEC PORTO - Instituto Superior de Tecnologias Avançadas do Porto*

`[ v2.0-stable ]` `[ Cybersecurity ]` `[ PHP/Python/JS ]`

</div>

---

### SOBRE O PROJETO

> **O EyeWeb Reborn é a evolução da arquitetura de segurança EyeWeb.**
> Desenvolvido para elevar a gestão de dados e proteção digital, esta plataforma oferece uma solução robusta para análise de websites, auditoria de credenciais e deteção de fugas de informação.

O sistema integra **Agentes Reativos** (sistemas inteligentes de resposta) que auxiliam na mitigação de riscos em tempo real, servindo tanto o utilizador comum quanto a administração do sistema.

---

### FUNCIONALIDADES DO SISTEMA

#### :: MÓDULO DE UTILIZADOR (CLIENT)

* **Análise de Websites (URL Intelligence)**
    * Verificação em tempo real de *phishing*, *malware* e ligações suspeitas via APIs de segurança e IA.
* **Auditoria de Credenciais (Credential Guard)**
    * **Palavras-passe:** Avaliação de entropia e verificação de exposição em bases de dados de *leaks* (implementação de **K-Anonymity** e **Hashing**).
    * **Identidade:** Verificação cruzada de E-mails e Números de Telemóvel em bases de dados comprometidas.
* **Agente Reativo (Assistente Virtual)**
    * Interface de chat automatizada para orientação de segurança e suporte à navegação.

#### :: MÓDULO DE ADMINISTRAÇÃO (ROOT)

* **Painel de Controlo (Dashboard)**
    * Visualização centralizada de logs, tráfego e métricas de segurança.
* **Agente de Segurança (Watchdog)**
    * Monitorização ativa de ligações, bloqueio de tentativas de intrusão e alertas de vulnerabilidades críticas (`SQL Injection`, `DDoS`, `Brute Force`).
* **Autenticação Reforçada (Security Core)**
    * Implementação de **MFA (Multi-Factor Authentication)** via script Python proprietário.
    * Controlo de Acesso Baseado em Funções (**RBAC**).

---

### ARQUITETURA DE SEGURANÇA

A privacidade e integridade dos dados são asseguradas pelas seguintes implementações:

1.  **Criptografia:** Nenhum dado sensível é armazenado em texto limpo. Utilização de **SHA-256**.
2.  **Anonimato:** Implementação de **K-Anonymity** para verificação de credenciais sem transmissão da palavra-passe completa.
3.  **Transporte:** Todo o tráfego é encapsulado via **HTTPS**.
4.  **Defesa:** Sanitização rigorosa de *inputs* e *Rate Limiting* no backend.

---

### STACK TECNOLÓGICA

| Camada | Tecnologias |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP, Node.js |
| **Database** | MySQL (SQL) |
| **Scripting** | Python 3 (Token Generation) |
| **Integrações** | External Security APIs |

---

### AUTORES
Desenvolvido por:

Francisco Rafael Carocinho Ribeiro - [ 2024123 ]

José Samuel da Rocha Oliveira - [ 2024172 ]

Tiago Filipe Sousa Carvalho - [ 2024180 ]

Ana Rita da Silva Monteiro - [ 2024041 ]

Vanina Kollen - [ 2024056 ]

Orientação Docente: Hélder Pinto, Vitor Santos, Vitor Rocha, Ricardo Moura.
-------------

## [ ENGLISH - EN ]

<div align="center">

# EYEWEB REBORN

**FINAL CYBERSECURITY PROJECT | 2ND YEAR CTESP**
*ISTEC PORTO - Instituto Superior de Tecnologias Avançadas do Porto*

`[ v2.0-stable ]` `[ Cybersecurity ]` `[ PHP/Python/JS ]`

</div>

---

### ABOUT THE PROJECT

> **EyeWeb Reborn is the evolution of the EyeWeb security architecture.**
> Designed to elevate digital data management and protection, this platform offers a robust solution for website analysis, credential auditing, and data leak detection.

The system integrates **Reactive Agents** (intelligent response systems) that assist in real-time risk mitigation, serving both the standard user and system administration.

---

### SYSTEM FEATURES

#### :: USER MODULE (CLIENT)

* **Website Analysis (URL Intelligence)**
    * Real-time verification of *phishing*, *malware*, and suspicious links via security APIs and AI.
* **Credential Audit (Credential Guard)**
    * **Passwords:** Entropy evaluation and exposure check in leak databases (implementing **K-Anonymity** and **Hashing**).
    * **Identity:** Cross-reference verification of Emails and Phone Numbers in compromised databases.
* **Reactive Agent (Virtual Assistant)**
    * Automated chat interface for security guidance and navigation support.

#### :: ADMIN MODULE (ROOT)

* **Control Panel (Dashboard)**
    * Centralized visualization of logs, traffic, and security metrics.
* **Security Agent (Watchdog)**
    * Active monitoring of connections, intrusion attempt blocking, and alerts for critical vulnerabilities (`SQL Injection`, `DDoS`, `Brute Force`).
* **Enhanced Authentication (Security Core)**
    * **MFA (Multi-Factor Authentication)** implementation via proprietary Python script.
    * Role-Based Access Control (**RBAC**).

---

### SECURITY ARCHITECTURE

Data privacy and integrity are ensured through the following implementations:

1.  **Encryption:** No sensitive data is stored in plain text. Usage of **SHA-256**.
2.  **Anonymity:** **K-Anonymity** implementation for credential verification without transmitting the full password.
3.  **Transport:** All traffic is encapsulated via **HTTPS**.
4.  **Defense:** Rigorous *input* sanitization and backend *Rate Limiting*.

---

### TECH STACK

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP, Node.js |
| **Database** | MySQL (SQL) |
| **Scripting** | Python 3 (Token Generation) |
| **Integrations** | External Security APIs |

---

### AUTHORS
Developed by:

Francisco Rafael Carocinho Ribeiro - [ 2024123 ]

José Samuel da Rocha Oliveira - [ 2024172 ]

Tiago Filipe Sousa Carvalho - [ 2024180 ]

Ana Rita da Silva Monteiro - [ 2024041 ]

Vanina Kollen - [ 2024056 ]

Faculty Supervision: Hélder Pinto, Vitor Santos, Vitor Rocha, Ricardo Moura.
