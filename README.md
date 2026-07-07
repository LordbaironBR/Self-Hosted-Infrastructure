# 🌐 Self-Hosted Infrastructure: Autonomia e Privacidade Digital
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![Open Source](https://img.shields.io/badge/Open_Source-Community-green?style=for-the-badge)
---

## Habilidades utilizadas:

* **Domínio de Linux (Debian):**
* **Conteinerização (Docker-Compose):**
* **Redes e Tráfego Seguros:**
* **Proxy Reverso e SSL:**
* **Controle de DNS:**

---
> **Nota:** Estou fazendo uma Playlist no Youtube, com o objetivo de ensinar e fazer tudo na pratica em uma VM.
> Link:

## Nosso Ecossistema Atual (O que roda no servidor?)

Alguns APPs que recomendo para iniciar nossa infra

> **Nota:** Não irei documentar os APPs detalhadamente aqui, pretendo fazer um repositório para cada APP em especifico como o Mailcow e repositórios para alguns conjuntos de APP como "rr" e automações de integração, neste projeto irei focar na infraestrutura do servidor.

### 🛡️ Segurança e Governança
* **Vaultwarden:** Nosso gerenciador de senhas autohospedado.
* **Pi-Hole:** Bloqueio de DNS. Bloquearemos servidores de telemetria e requisições desnecessaria na rede. (Porem precisamos ter o servidor alvo em mãos para bloquea-los, a comunidade ajudou muito nisso, fique tranquilo)
* **Mailcow:** Controle total sobre e-mails institucionais e pessoais, com sistema de máscaras e catch-all.

### 🏠 Automação Residencial e IoT
* **Home Assistant:** Ambiente de automação residencial.
* **Integração N8N & Hermes:** Orquestração de APIs e controle por voz avançado.


### 💬 Comunicação
* **Jitsi & Chatwoot (com API Evolution):** Alternativas open-source para videoconferências sem limite de tempo e centralização de atendimento.

### 🍿 Mídia e Broadcast
* **Jellyfin & Ecossistema "rr":** Pipeline completo para gerenciamento, download e recomendação de mídias de forma automatizada e indexada.
* **Owncast:** Servidor de streaming de vídeo autohospedado.

### 🛠️ Gestão e Produtividade
* **Homepage:** O nosso painel de controle visual centralizando o acesso a tudo.
* **Gitea, Trilium & Excalidraw:** Nosso próprio "GitHub", cadernos de anotações e quadros brancos digitais para documentar a vida e o código.
* **Portainer & Glances:** Monitoramento e gestão do Servidor/Docker.

## Primeiros passos

- preparação do ambiente (rasberry pi, computador velho, servidor comprado, celular, VM) (linkar o arquvio /server/00-Ambiente)
- Instalação do sistema operacional (linkar /server/01-Debian)
