# ♻️ MVP — Cooperativa de Reciclagem Vale Verde

Aplicação Web Progressiva (PWA / Mobile-First) desenvolvida para otimizar o agendamento de pedidos de recolha seletiva e a roteirização diária da frota da **Cooperativa de Reciclagem Vale Verde**, contribuindo para o **ODS 11 (Cidades e Comunidades Sustentáveis)**.

## 🎯 Objetivo do Projeto
Substituir o registo manual em cadernos físicos e mensagens informais por uma plataforma centralizada que elimina a perda de solicitações e reduz deslocações duplicadas dos camiões de recolha.

## 🛠️ Tecnologias Utilizadas
- **Back-end:** Python 3.12 + Microframework Flask 3.0
- **Persistência e ORM:** PostgreSQL 16 (Supabase) + SQLAlchemy 2.0
- **Front-end:** HTML5, CSS3 e JavaScript (PWA com suporte offline via Service Workers)

## 📂 Estrutura Prevista
- `app/` — Aplicação principal, rotas REST e regras de ordenação geográfica
- `models/` — Entidades relacionais (`usuarios`, `rotas_diarias`, `pedidos_recolha`)
- `templates/` e `static/` — Interfaces responsivas de alto contraste e ficheiros PWA
