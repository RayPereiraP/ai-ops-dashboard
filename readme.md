# 📊 AI Ops Dashboard & Churn Radar

Aplicação web de monitoramento logístico construída inteiramente através de **Vibe Coding** utilizando `v0.dev`, `Next.js` e `Tailwind CSS`. 

---

## 🎯 Contexto e Propósito (Trilha AI Builder)

Como AI Builder, a velocidade de prototipação é crucial. Quando a área de Operações de um app de delivery precisa visualizar anomalias na rede de parceiros, o ciclo tradicional de design, aprovação, front-end e deploy pode levar semanas. 

Este projeto demonstra como utilizar Engenharia de Prompt para gerar um painel analítico funcional de ponta a ponta em questão de minutos, permitindo que a área de negócios interaja com os dados imediatamente.

### 🛠️ O que foi construído
1. **Painel de KPIs:** Visão imediata de SLAs quebrados e taxas de cancelamento.
2. **Radar de Risco:** Tabela dinâmica que isola os parceiros (restaurantes) que estão falhando na operação diária, categorizados por risco de churn.
3. **AI Copilot Integrado:** Uma interface de chat nativa onde o gestor pode consultar a base de dados usando linguagem natural para tomar decisões de contenção.

---

## 🏗️ Como foi desenvolvido (Vibe Coding)

Este dashboard não foi codificado linha a linha. Ele foi orquestrado utilizando ferramentas de IA generativa para UI.

1. **Plataforma:** v0.dev (by Vercel)
2. **Stack Gerada:** React, Next.js, Tailwind CSS, Lucide Icons, Shadcn UI.
3. **Prompting:** O prompt utilizado para gerar esta interface estabeleceu regras estritas de design system (dark mode, liquid metal aesthetic) e exigiu a inserção de métricas específicas do modelo de negócios de delivery.
   
*(Veja o prompt original completo no arquivo `prompts/v0_generation_prompt.txt`)*

---

## 🚀 Como visualizar e rodar

### Opção 1: Rodar Localmente
Certifique-se de ter o Node.js instalado.
\`\`\`bash
git clone https://github.com/seu-usuario/ai-ops-dashboard.git
cd ai-ops-dashboard
npm install
npm run dev
\`\`\`
Abra `http://localhost:3000` no seu navegador.

### Opção 2: Visualizar no v0
Cole o conteúdo do `v0_generation_prompt.txt` diretamente no [v0.dev](https://v0.dev/) para ver a IA gerando, iterando e renderizando o código em tempo real.