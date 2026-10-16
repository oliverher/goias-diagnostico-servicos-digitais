# Diagnóstico de Serviços Digitais — Goiás

Site estático (GitHub Pages) + Supabase. Navegação por abas:

- **Início** — visão geral e atalhos.
- **Orientações** — guia de preenchimento.
- **Responder** — escolha do órgão e formulário das perguntas dele (salvamento automático, exportar XLSX).
- **Andamento** — progresso por órgão e por bloco; exporta o consolidado em XLSX.
- **Respostas** — consulta, com filtros, às respostas de todos os órgãos.

Arquivos: `index.html` (aplicação), `questions.json` (64 perguntas e o órgão de cada uma, campo `orgaos`), `orientacoes.html` (redireciona para a aba Orientações).

O acesso é aberto por decisão do programa: qualquer pessoa pode ver e editar as respostas de qualquer órgão.
