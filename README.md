# Atualização do Projeto EyeWeb

# [ README.md ]

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

### INSTALAÇÃO E DEPLOY

```bash
# 1. BASE DE DADOS
Importar o ficheiro 'eyeweb.sql' para o servidor MySQL/MariaDB.

# 2. CONFIGURAÇÃO
Editar o ficheiro 'config.php':
- Definir credenciais da DB ($DB_HOST, $DB_USER, etc.)
- Configurar variáveis de ambiente (AGENT_PUBLIC_TOKEN)

# 3. SERVIDOR
Carregar ficheiros para o diretório público (public_html/www).
ATENÇÃO: O suporte a SSL/HTTPS é obrigatório.

# 4. ADMINISTRAÇÃO
Executar o script Python localmente para gerar tokens MFA para acesso root.


### AUTORES
Desenvolvido por:

Francisco Rafael Carocinho Ribeiro - [ 2024123 ]

José Samuel da Rocha Oliveira - [ 2024172 ]

Tiago Filipe Sousa Carvalho - [ 2024180 ]

Ana Rita da Silva Monteiro - [ 2024041 ]

Vanina Kollen - [ 2024056 ]

Orientação Docente: Hélder Pinto, Vitor Santos, Vitor Rocha, Ricardo Moura.
