# Gustavo Vitória de Camargo

**Fundador da [KRYPTA](https://krypta.online) · desenvolvedor de software full-stack · automação e agentes de IA**
Brasil · trabalho remoto

Coloco sistema em produção de ponta a ponta: modelo de dados, backend, interface, servidor, HTTPS, backup e monitoramento. Sem apresentação no lugar de software.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gustavo_Vitória_de_Camargo-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavo-vitoria-de-camargo-0922a6427)
[![KRYPTA](https://img.shields.io/badge/krypta.online-071A2D?style=flat&logo=googlechrome&logoColor=00E5FF)](https://krypta.online)

---

## No ar agora

**[Krypta Barber](https://barber.krypta.online)** — SaaS de gestão para barbearias
Agenda, ficha de clientes, agendamento online com sinal por Pix e relatórios, instalável como app (PWA).
Multi-tenant num Postgres único com isolamento por Row-Level Security; pagamento em modelo marketplace, com o dinheiro do cliente final caindo direto na conta do barbeiro via OAuth do Mercado Pago.
`Next.js 16` `TypeScript` `PostgreSQL + RLS` `Prisma` `Mercado Pago` `nginx` `Linux`

**Reserva de frota multi-unidade** — sistema interno para um cliente do setor de engenharia
Reescrita de um sistema legado: login por usuário com troca de senha no primeiro acesso, separação por unidade e migração integral do histórico de reservas. Roda em VPS dedicada a cargas de cliente.
`React` `Vite` `TypeScript` `Express` `PostgreSQL` `systemd` `Let's Encrypt`

**Hermes** — orquestração de agentes de IA em infraestrutura própria
29 perfis de especialista rodando 24h numa VPS, com bot no Discord e painel. É a operação interna da KRYPTA.

## Outros trabalhos

| Projeto | O que resolve | Stack |
|---|---|---|
| Validação de notas fiscais contra ERP | Lê orçamentos e NFs em PDF, extrai os itens e cruza com o cadastro do ERP. Uma trava determinística de medidas (ex.: `16MM`, `35KV`) roda antes da similaridade semântica por embeddings, para não casar itens parecidos de bitola diferente. | Python · pdfplumber · sentence-transformers · Node.js |
| GeoRef | Plugin de CAD que alinha desenhos 2D a coordenadas reais (SIRGAS2000/WGS84 → UTM) e insere imagem de satélite georreferenciada dentro do desenho. Sem nenhuma dependência paga. | C# · .NET · WPF · WebView2 · ProjNET |
| GVC Pulse | Editor de código com quatro agentes de IA em sequência; cada agente só recebe as ferramentas que pode usar, então o confinamento não depende do prompt. Binário de ~25 MB. | Rust · Tauri v2 · React · Monaco |
| Suíte de BI | Consultas SQL para Power BI e um robô que atualiza e publica os relatórios sem depender de API do Azure. | PostgreSQL · Python · PowerShell |
| Estacionamento SaaS | Plataforma multi-tenant com app Android para maquininhas POS (Gertec). | FastAPI · Android · PostgreSQL |

Os repositórios desses projetos são privados, por serem de cliente ou de trabalho. Posso mostrar o código numa conversa.

## Ferramentas do dia a dia

TypeScript, React, Next.js, Node.js · Python, FastAPI · C# / .NET · Rust / Tauri
PostgreSQL, Prisma, Supabase · Docker, PM2, nginx, systemd, VPS Linux, Tailscale · Vercel
Claude Code e agentes de IA como parte do fluxo de engenharia, com revisão humana antes de produção

## Contato

Projetos, parcerias ou uma proposta de trabalho: [LinkedIn](https://www.linkedin.com/in/gustavo-vitoria-de-camargo-0922a6427) ou [krypta.online](https://krypta.online).
