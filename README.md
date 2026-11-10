# ☁️ Meu Primeiro Pipeline de CI/CD (Deploy Automático)

## 📌 Sobre o Projeto
Este é um projeto prático de introdução a conceitos de DevOps e Cloud Computing. O objetivo foi estabelecer uma integração contínua (CI/CD) simples: um repositório no GitHub conectado a um serviço de nuvem (Render), permitindo que qualquer alteração no código seja automaticamente refletida em produção.

## 🔗 Link do Projeto Online
[Clique aqui para ver a página no ar](https://meu-primeiro-deploy.onrender.com/)

## 🛠️ Tecnologias Utilizadas
* **Controle de Versão:** Git / GitHub
* **Hospedagem e Cloud:** Render (Plataforma como Serviço - PaaS)
* **Linguagem:** HTML5 básico

## 🚀 Como funciona a Arquitetura
1. O código-fonte estático (`index.html`) fica hospedado no GitHub.
2. O Render monitoriza o repositório.
3. Sempre que um novo *commit* é feito na ramificação principal (main), o Render deteta a mudança, reconstrói o ambiente e atualiza a página no ar automaticamente, sem necessidade de intervenção manual.
