# GUUH SC — Voz da Quebrada 012 (Site Oficial)

Site oficial do artista e MC **Guuh SC** (São José dos Campos - SP / DDD 012). Desenvolvido com React, Vite, TypeScript e Tailwind CSS, otimizado para SEO local e regional, com integração direta para contratação via WhatsApp, streaming no Spotify e lançamentos audiovisuais no YouTube.

## 🚀 Tecnologias Utilizadas

- **React 19** + **TypeScript**
- **Vite** (bundler de alta performance)
- **Tailwind CSS v4**
- **Lucide React** (iconografia moderna)
- **Schema.org JSON-LD** (`MusicGroup` & `Person` com suporte avançado a SEO local)
- **GitHub Actions** (deploy automático para GitHub Pages)

## 📌 Principais Funcionalidades

- **Identidade Visual Dark Cyber-Funk**: Logo oficial em neon rosa com backdrop radial glow e animações fluídas.
- **Player Integrado do Spotify**: Player oficial com a discografia e lançamentos pela Love Funk e Cria Hit.
- **SEO Regional Avançado**:
  - Otimização priorizada: São José dos Campos (SJC) → Taubaté → Jacareí → Vale do Paraíba → Litoral Norte de SP → São Paulo Capital → Rio de Janeiro → Capitais Brasileiras.
  - Metadados geográficos (`geo.region`, `geo.placename`, `geo.position`, `ICBM`).
  - `sitemap.xml` e `robots.txt` inclusos.
- **Atendimento e Contratação Direta**:
  - Botão de WhatsApp interativo para assessoria rápida.
  - Formulário com redirecionamento direto para o WhatsApp preenchido com os detalhes da proposta.

## 💻 Instalação e Desenvolvimento Local

```bash
# 1. Instalar as dependências
npm install

# 2. Executar o servidor de desenvolvimento
npm run dev

# 3. Compilar para produção
npm run build
```

## 🌐 Deploy

O projeto conta com GitHub Actions configurado em `.github/workflows/deploy.yml` para compilar e publicar automaticamente no GitHub Pages a cada atualização na branch `main`.