# Diagnóstico de Serviços Digitais — Goiás

Aplicação estática (HTML + JS) publicada no GitHub Pages. As respostas são gravadas no Supabase.

- `index.html` — aplicação (visão do órgão `?t=TOKEN` e visão de administração `?admin=TOKEN`).
- `questions.json` — as 64 perguntas e o órgão responsável por cada uma (campo `orgaos`).

Os tokens de acesso **não** estão neste repositório; ficam no banco (tabelas `orgaos` e `config`, sem acesso público).
Alterar quem responde cada pergunta: editar o campo `orgaos` em `questions.json`.
