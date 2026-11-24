# Henrique Otta Rodrigues

**Desenvolvedor Full Stack** | TypeScript, React, Node.js, PostgreSQL | IA aplicada (LLMs e agentes)

Remoto, ou presencial/híbrido em Porto Alegre e região e em Florianópolis. Sapucaia do Sul, RS.

[LinkedIn](https://www.linkedin.com/in/henrique-otta-rodrigues) · [Portfólio interativo](https://henrique-otta-rodrigues.vercel.app) · [Pipeline CRM ao vivo](https://user-management-api-gray.vercel.app)

---

Vim do chão de fábrica: passei anos operando e ajustando injetoras e levei pra programação o que aprendi lá, que é processo, atenção a detalhe e foco em resolver o problema de verdade.

Hoje trabalho em duas frentes:

- **Desenvolvimento web:** manutenção e evolução de um sistema empresarial em produção (React, Node.js, TypeScript, PostgreSQL). Eliminei consultas N+1 em listagens operacionais, criei relatórios de produção em tempo real e exportação para Excel e PDF.
- **IA aplicada:** como **AI Implementation Specialist (Gestor de IA)** na Carmillion, cuido de uma carteira de 20 clientes: levanto a necessidade de cada revenda de veículos, configuro o agente de atendimento com LLM, faço a engenharia de prompts e integro a plataforma com Mercado Livre, OLX e Webmotors. No dia a dia uso Python e Spring Boot.

## Projetos

**[Pipeline CRM](https://github.com/RikkyRS/user-management-api)** · [demo ao vivo](https://user-management-api-gray.vercel.app) (botão "Entrar como demonstração")
CRM multiempresa com API REST e painel web: funil de leads por etapa, conversas do WhatsApp junto do lead, autenticação JWT com sessão em cookie HttpOnly e permissões por papel em cada empresa.
`TypeScript` `Node.js` `Express` `PostgreSQL` `Prisma` `Next.js` `Vercel`

**[Agente do CRM](https://github.com/RikkyRS/agente-crm)**
Agente de IA que opera o Pipeline CRM em linguagem natural e sempre pede confirmação antes de alterar algo. O modelo só pede a ferramenta; quem valida e executa é o código. Tool calling do zero, MCP, evals 10/10 e testes no CI.
`TypeScript` `Ollama` `MCP` `GitHub Actions`

**[JARVIS](https://github.com/RikkyRS/Jarvis)**
Runtime open source que governa agentes de IA no desenvolvimento: a IA propõe, o código autoriza. Política de risco, aprovação de uso único, auditoria com hash encadeado e isolamento em container. 210 testes, e o CI roda o isolamento num Docker de verdade.
`TypeScript` `Node.js` `SQLite` `Docker` `Vitest`

**[Pergunte ao meu currículo](https://github.com/RikkyRS/pergunte-ao-curriculo)**
RAG que responde sobre a minha carreira usando só o currículo, cita a fonte e admite quando não sabe. Busca na seção certa em 10/10; avaliar busca e geração separadamente mostrou qual das duas metades falhava.
`TypeScript` `PostgreSQL` `pgvector` `LLM`

**[Site da Barber House](https://barberhouse-barbearia.vercel.app)**
Site de uma rede de barbearias com 6 unidades: mapa interativo, botão que acha a unidade mais perto e pedido direto pelo WhatsApp da unidade.
`React` `TypeScript` `Vite` `Vercel`

## Stack

| | |
|---|---|
| **Principal** | TypeScript, JavaScript, React, Node.js, PostgreSQL |
| Back-end | Express, Prisma, Zod, APIs REST, RBAC, Python, Spring Boot |
| Front-end | HTML, CSS, Vite |
| IA | LLMs, agentes, tool calling, MCP, RAG, engenharia de prompts, integrações de APIs |
| Qualidade e entrega | Vitest, GitHub Actions, Docker, Vercel, Render, Git Flow |

## Formação

Engenharia de Software, UniCesumar (cursando) · Técnico em Plásticos, IFSul Sapucaia do Sul

Os repositórios mais antigos daqui (Odin Project, Ruby) ficam de propósito: mostram de onde eu comecei.
