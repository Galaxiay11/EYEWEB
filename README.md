# Atualização do Projeto EyeWeb

## Contexto

Este repositório corresponde à atualização do projeto EyeWeb, desenvolvida no âmbito do 2º Ano de CTeSP em Cibersegurança (ISTEC Porto).

O projeto original **EyeWeb** era uma ferramenta web que analisava palavras-passes, emails, sites e numeros de telemóvel.
Esta nova versão  **EyeWeb Reborn**  possui novas funcionalidades, melhorias de desempenho e uma integração inteligente de um **Agente Reativo**.

---

##  Principais Melhorias e Novidades

### Integração de um Agente Reativo Inteligente
- Novo assistente virtual integrado no painel do administrador.  
- Capaz de responder a perguntas em tempo real (ex.: “O IP foi vazado?”, “A senha é segura?”).  
- Atua como apoio de segurança contínuo, pois ajuda na deteção de vulnerabilidades e gestão do site.  
- Implementado com limites de contexto para evitar respostas incorretas ou inseguras.

### Reforço de Segurança no Painel de Administração
- Implementação de autenticação em dois fatores (MFA).  
- Adoção de controlo de permissões por função (RBAC).  
- Introdução de confirmação dupla para comandos críticos (bloqueio de IPs, alterações de firewall).  
- Acesso ao painel restrito.  
- Criação de registos de atividade (logs) seguros e detalhados.

### Medidas Gerais de Segurança
- HTTPS obrigatório para todas as comunicações.  
- Sanitização de inputs e rate limiting para prevenir abusos e injeções de código.  
- Nenhum dado sensível do utilizador é armazenado, todas as análises são temporárias e seguras.  

### Melhoria de Desempenho e Estabilidade
- Código otimizado e ambiente de desenvolvimento atualizado.  
- Melhor integração entre frontend (HTML/CSS) e backend (Node.js + PostgreSQL).  
- Estrutura modular para facilitar futuras expansões (ex.: app móvel, alertas automáticos).  


---

## Estrutura e Tecnologias

| Camada | Tecnologia |

|--------|-------------|

| **Frontend** | HTML5, CSS3 |

| **Backend** | Node.js |

| **Base de Dados** | PostgreSQL |

| **Ferramentas** | VS Code, GitHub, WhatsApp (comunicação interna) |

---

## Testes Realizados

- **Testes Unitários** – verificação de componentes individuais.  
- **Testes de Integração** – funcionamento conjunto de módulos.  
- **Testes de Usabilidade** – realizados com utilizadores para avaliar a facilidade de uso.  
- **Testes de Segurança** – deteção e correção de vulnerabilidades (ex.: SQL Injection, brute force).  

---

## Mudanças Técnicas (Resumo)

| Área | Versão Anterior | EyeWeb Reborn |
|------|------------------|----------------|
| **Segurança de Login** | Apenas autenticação base | MFA + RBAC + logs |
| **Monitorização** | Manual | Em tempo real via Agente Reativo |
| **Interface** | Básica | Atualizada com animações e design limpo |
| **Comunicação** | Sem suporte inteligente | Agente Reativo integrado |
| **Armazenamento de dados** | Local e simples | PostgreSQL + sanitização e segurança reforçada |
| **Desempenho** | Moderado | Otimizado com Node.js atualizado |
| **Privacidade** | Parcial | Total — nenhuma informação pessoal é guardada |

---

## Melhorias Planeadas / Futuras Atualizações

- Suporte a múltiplos idiomas;  
- Aplicação móvel (Android/iOS);  
- Alertas automáticos por e-mail;  
- Expansão de tipos de análise de segurança (ex.: headers, reputação de IPs, domínios);  
- Melhorar a inteligência contextual do Agente Reativo.

---

## Contexto Académico

> Este projeto foi desenvolvido no âmbito académico do curso **CTeSP de Cibersegurança** do **ISTEC Porto**, em 2025.  
> É uma evolução direta do **EyeWeb**, com foco em modernização tecnológica, melhoria de segurança e integração de inteligência artificial reativa.

---

## Licença

Este projeto é de caráter académico e educativo.  
O código pode ser reutilizado e adaptado com referência à equipa desenvolvedora e ao ISTEC Porto.


