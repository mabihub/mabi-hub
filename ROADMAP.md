# Roadmap de Desenvolvimento do MABI HUB

Este arquivo descreve o plano de implementação para migrar o frontend para Next.js 14 com TypeScript e integrar os serviços existentes.

## Etapas Iniciais
1. Configurar ambiente Next.js 14 com TypeScript e TailwindCSS.
2. Recriar layout básico e design system utilizando shadcn/ui.
3. Implementar autenticação com NextAuth e conectar ao PostgreSQL via Prisma.
4. Migrar módulos existentes (Chamadas, Leads, Fluxos, Integrações, Faturamento, Configurações, Marketplace) para a estrutura de rotas da App Router.
5. Configurar deploy contínuo no Vercel com preview para cada Pull Request.

## Back‑end e Integrações
- Revisar e adaptar endpoints da Core API, Voice Engine, Flow Engine e Sistema de Integrações para suportar o frontend Next.js.
- Configurar banco de dados Postgres e Redis com Prisma.

## Monitoramento e Testes
- Implementar testes unitários e de integração.
- Preparar pipeline de CI/CD com GitHub Actions e deploy em ambiente de staging.
- Adicionar instrumentação para métricas e logs.

## IA Conversacional
- Após MVP, iniciar integração com LangChain e modelos LLM (Gemini/Claude).
