# Atualização do Projeto EyeWeb

## Contexto
Este repositório corresponde à atualização do projeto **EyeWeb**, desenvolvido no âmbito do **2.º Ano do CTeSP em Cibersegurança do ISTEC Porto**.

O projeto original **EyeWeb** era uma ferramenta web que permitia analisar palavras-passe, endereços de e-mail, sites e números de telemóvel.  
A nova versão, chamada **EyeWeb Reborn**, inclui novas funcionalidades, melhorias de desempenho e a integração de um **Agente Reativo Inteligente**, que torna o sistema mais dinâmico e útil para o utilizador.

---

## Principais Melhorias e Novidades

### Integração de um Agente Reativo Inteligente
- Novo assistente virtual integrado no painel de administração.  
- Capaz de responder a perguntas em tempo real, como “O IP foi comprometido?” ou “Esta palavra-passe é segura?”.  
- Atua como apoio contínuo à segurança, auxilia na deteção de vulnerabilidades e na gestão do site.  
- Implementado com limites de contexto para evitar respostas incorretas ou inseguras.  

### Reforço de Segurança no Painel de Administração
- Implementação de autenticação multifator (MFA).  
- Adoção de controlo de permissões por função (RBAC).  
- Confirmação dupla para comandos críticos (bloqueio de IPs, alterações à firewall).  
- Acesso ao painel restrito a administradores autorizados.  
- Criação de registos de atividade (logs) detalhados e protegidos.  

### Medidas Gerais de Segurança
- Utilização obrigatória de HTTPS em todas as comunicações.  
- Sanitização de inputs e rate limiting para prevenir abusos e injeções de código.  
- Nenhum dado sensível de utilizadores é armazenado, todas as análises são temporárias e seguras.  

### Melhoria de Desempenho e Estabilidade
- Código otimizado e ambiente de desenvolvimento atualizado.  
- Integração melhorada entre o frontend (HTML/CSS) e o backend (Node.js + PostgreSQL).  
- Estrutura pensada para facilitar futuras expansões (ex.: aplicação móvel ou alertas automáticos).  

---

## Testes Realizados
- **Testes Unitários** – verificação de componentes individuais.  
- **Testes de Integração** – avaliação do funcionamento conjunto dos módulos.  
- **Testes de Usabilidade** – realizados com utilizadores para testar a facilidade de utilização.  
- **Testes de Segurança** – deteção e correção de vulnerabilidades (ex.: SQL Injection, ataques de força bruta).  

---

## Melhorias Futuras Planeadas
- Suporte a múltiplos idiomas.  
- Aplicação móvel (Android/iOS).  
- Alertas automáticos por e-mail.  
- Expansão dos tipos de análise de segurança (ex.: cabeçalhos HTTP, reputação de IPs e domínios).  
- Melhoria da inteligência contextual do Agente Reativo.  

---

## Contexto Académico
Este projeto foi desenvolvido no âmbito académico do **CTeSP de Cibersegurança do ISTEC Porto**, no ano letivo de **2025**.  
É uma evolução do EyeWeb original, com o foco na modernização tecnológica, reforço da segurança e integração de inteligência artificial reativa.  

---

## Licença
Este projeto é de caráter **académico e educativo**.  
O código pode ser reutilizado e adaptado, desde que seja feita referência à **equipa desenvolvedora** e ao **ISTEC Porto**.  

