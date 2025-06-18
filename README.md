# EyeWeb — Simulador de Avaliação de Segurança Digital
![EYEWEB-LOGOTIPO](https://github.com/user-attachments/assets/409fcb12-19e7-4f64-a9f6-8088e6e7531e)


## Descrição Geral

O **EyeWeb** é uma aplicação web desenvolvida no âmbito do curso de CTeSP em Cibersegurança (1.º ano), na unidade curricular de Base de Dados. O projeto visa criar uma ferramenta que permita aos utilizadores verificar a segurança de palavras-passe e websites, alertando para riscos e fornecendo sugestões de proteção. O projeto foi coordenado por **Ana Rita da Silva Monteiro**, na função de **Product Owner** e líder de equipa.

---

## Finalidade do Projeto

- Verificar se uma palavra-passe, número de telemóvel e email foram expostos em fugas de dados.
- Avaliar a integridade e reputação de websites.
- Alertar o utilizador para potenciais riscos.
- Fornecer uma interface simples, intuitiva e acessível.

---

## Equipa e Responsabilidades

| Ana Rita da Silva Monteiro | Product Owner, lider do projeto, desenvolvimento da interface, documentação | Galaxiay11


| José Samuel da Rocha Oliveira | Desenvolvimento do frontend, design gráfico, base de dados | Wodash34


| Tiago Filipe Sousa Carvalho | Backend, diagrama ER, base de dados | Tiago0612


| Vanina Kollen | Estruturação da base de dados, backend, relatório técnico | vankol06


| Francisco Rafael Carocinho Ribeiro | Funcionalidades, apoio técnico geral | Xico20230


| Emanuel Jorge Seixas Barbosa | Relatório técnico, estrutura da informação |

---

## Estrutura do Repositório
EyeWeb/

├── database/                 # Arquivos SQL do banco de dados


│   └── eyeweb.sql            # Arquivo fonte SQL (4KB)


│


├── public/                   # Arquivos acessíveis publicamente


│   ├── css/                  # Folhas de estilo


│   │   ├── about.css         # (2KB)


│   │   ├── admin.css         # (6KB)


│   │   ├── admin_data_base.css # (12KB)


│   │   ├── index.css         # (6KB)


│   │   └── login.css         # (3KB)


│   │


│   ├── js/                   # Arquivos JavaScript


│   │   ├── about.js          # (1KB)


│   │   ├── admin.js          # (2KB)


│   │   ├── admin_data_base.js # (1KB)


│   │   └── index.js          # (6KB)


│   │


│   ├── about.php             # (4KB)


│   ├── admin.php             # (8KB)


│   ├── admin_data_base.php   # (4KB)


│   ├── editor.php            # (7KB)


│   ├── eliminar.php          # (3KB)


│   ├── index.php             # (11KB)

│   ├── login.php             # (3KB)


│   └── logout.php            # (1KB)


│


├── logs/                     # Arquivos de log


│   └── log.txt               # Documento de texto (1KB)


│

├── README.md                 # Documentação do projeto



---

## Tecnologias Utilizadas

-Backend: PHP

-Frontend: HTML, CSS, JavaScript

-Banco de dados: MySQL (arquivo SQL fornecido)

-Servidor local: WAMP Server (Windows, Apache, MySQL, PHP)

---

## Modo de Utilização
1.Pré-requisitos:
   
-WAMP Server instalado (versão compatível com PHP 7.x/8.x)

-Navegador web moderno (Chrome, Firefox, Edge)

2.Instalação:

-Faça o download do ZIP do repositório

-Extraia o conteúdo para a pasta www do WAMP Server

-Importe o arquivo eyeweb.sql para o MySQL via phpMyAdmin

-Configure as credenciais do banco de dados nos arquivos PHP se necessário


3.Execução:

-Inicie o WAMP Server

-Acesse no navegador: http://localhost/EyeWeb/public/


**Requisitos Técnicos**

1.Servidor:

-WAMP Server (ou similar como XAMPP, LAMP)

-Apache 2.4+

-PHP 7.4+

-MySQL 5.7+ ou MariaDB 10.3+

2.Cliente:

-Navegador com suporte a HTML5 e CSS3

-Resolução mínima recomendada: 1024x768


**English Summary**
Project: EyeWeb — Digital Security Risk Checker

Overview:
EyeWeb is a web-based tool developed by first-year students of the Cybersecurity CTeSP program. Its goal is to analyze password security and identify malicious websites. The application alerts users about vulnerabilities and provides security suggestions.

**Main Features:**

- Password breach detection
- Website threat analysis
- No data is stored
- Simple, accessible interface


Team Leader: Ana Rita da Silva Monteiro (Product Owner) - Galaxiay11
