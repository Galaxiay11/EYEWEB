# Atualização do Projeto EyeWeb
## [ PORTUGUÊS - PT ]


# EYEWEB REBORN

**PROJETO FINAL DE CIBERSEGURANÇA | 2º ANO CTESP**
*| ISTEC PORTO - Instituto Superior de Tecnologias Avançadas do Porto*

</div>

---

### SOBRE O PROJETO

> **O EyeWeb Reborn é uma atualização do projeto EyeWeb.**



Foi desenvolvido para elevar a gestão de dados e proteção digital, oferencendo uma solução robusta para análise de websites, auditoria de credenciais e deteção de fugas de informação.
O sistema integra **Agentes Reativos** (sistemas inteligentes de resposta) que auxiliam na minimizção de riscos em tempo real, servindo tanto o utilizador comum quanto a administração do sistema.

---

### FUNCIONALIDADES DO SISTEMA

#### MÓDULO DO UTILIZADOR 

* **Análise de Websites**
    * Verificação em tempo real de *phishing*, *malware* e ligações suspeitas.
* **Auditoria de Credenciais**
    * **Palavras-passe:** Auditoria de palavras-passe com avaliação de força, hashing e verificação segura através de
K-Anonymity.
    * **Identidade:** Verificação de E-mails e Números de Telemóvel em bases de dados comprometidas.
* **Agente Reativo (Assistente Virtual)**
    * Interface de chat automatizada para orientação de segurança e suporte à navegação.

#### MÓDULO DO ADMINISTRAÇÃO 

* **Painel de Controlo**
    * Visualização centralizada de logs, tráfego e métricas de segurança.
* **Agente de Segurança**
    * Monitorização ativa de ligações, bloqueio de tentativas de intrusão e alertas de vulnerabilidades críticas (`SQL Injection`, `DDoS`, `Brute Force`).
* **Autenticação Reforçada**
    * Implementação de **MFA (Multi-Factor Authentication)**.
    * Controlo de Acesso Baseado em Funções.

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

**Orientação Docente:** Hélder Pinto, Vitor Santos, Vitor Rocha, Ricardo Moura.





-------------

## [ ENGLISH - EN ]


# EYEWEB REBORN

**FINAL CYBERSECURITY PROJECT | 2ND YEAR CTESP**
*| ISTEC PORTO - Instituto Superior de Tecnologias Avançadas do Porto*

</div>

---

### ABOUT THE PROJECT

> **EyeWeb Reborn is an updated version of the EyeWeb project.**

It was developed to enhance data management and digital protection, providing a robust solution for website analysis, credential auditing, and data leak detection.
The system integrates **Reactive Agents** (intelligent response systems) that help minimize risks in real time, serving both regular users and system administrators.

---

### SYSTEM FEATURES

####USER MODULE

* **Website Analysis**
    * Real-time verification of *phishing*, *malware*, and suspicious links.
* **Credential Audit**
    * **Passwords:** Password auditing with strength evaluation, hashing, and secure verification through **K-Anonymity**.
    * **Identity:** Cross-reference verification of Emails and Phone Numbers in compromised databases.
* **Reactive Agent**
    * Automated chat interface for security guidance and navigation support.

#### ADMIN MODULE

* **Control Panel**
    * Centralized visualization of logs, traffic, and security metrics.
* **Security Agent**
    * Active monitoring of connections, intrusion attempt blocking, and alerts for critical vulnerabilities (`SQL Injection`, `DDoS`, `Brute Force`).
* **Enhanced Authentication**
    * **MFA (Multi-Factor Authentication)** implementation.
    * Role-Based Access Control.

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

**Faculty Supervision:** Hélder Pinto, Vitor Santos, Vitor Rocha, Ricardo Moura.
