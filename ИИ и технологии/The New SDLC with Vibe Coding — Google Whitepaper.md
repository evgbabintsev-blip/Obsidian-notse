---
title: "The New SDLC with Vibe Coding — Google Whitepaper"
created: 2026-06-18
updated: 2026-06-18 02:34
source: joplin
---

📖 **The New SDLC with Vibe Coding** — Google whitepaper (Май 2026)

**Авторы:** Addy Osmani, Shubham Saboo, Sokratis Kartakis (Google)
**Дизайн:** Michael Lanning
**Контрибьюторы:** Elia Secchi, Julia Wiesinger, Anant Nawalgaria

**Ссылки:**
- Оригинал: https://www.kaggle.com/whitepaper-the-new-SDLC-with-vibe-coding
- PDF: https://raw.githubusercontent.com/doggy8088/the-new-sdlc-with-vibe-coding/main/The%20New%20SDLC%20With%20Vibe%20Coding_Day_1.pdf
- GitHub (PDF + перевод): https://github.com/doggy8088/the-new-sdlc-with-vibe-coding

---

Основная мысль: программирование превращается в задачу по корректному формулированию намерения. Разработчик говорит что нужно сделать, машина решает как.

**Оглавление:**
1. Introduction
2. Why this paper, why now
3. Who this paper is for
4. The shift from syntax to intent
5. AI Agents: A Quick Refresher
6. What is vibe coding?
7. The spectrum: vibe coding to agentic engineering
8. Context engineering: the real skill
9. The new software development life cycle
10. The factory model
11. Harness Engineering: What surrounds the model
12. The developer's evolving role: conductors and orchestrators
13. The 80% problem
14. Coding agents in practice
15. Production-ready Agents
16. The Economics of AI Development
17. Where to start
18. Conclusion: Intent as the new Interface

---

🔄 **Спектр: вайб-кодинг → агентная инженерия**
Вайб-кодинг — «написал промпт, принял что дали, сломалось — скопипастил ошибку обратно». Агентная инженерия — спецификации, тесты, гардрейлы, оценка траектории, человеческий надзор. Разница не в инструментах, а в дисциплине.

Три типа кодинг-агентов:
- Editor agents — в IDE, пишут/редактируют код
- Terminal agents — в CLI, запускают команды, дебажат
- Background agents — фоновые задачи, обследование кода, CI

🧠 **Контекстная инженерия — ключевой навык**
Качество кода зависит не от сложности промпта, а от качества контекста: AGENTS.md, файлы правил, память, навыки, RAG. Статический vs динамический контекст — инженерный компромисс, который надо версионировать как код.

⚙️ **Модель — лишь двигатель. Харнес — вся остальная машина**
Промпты, инструменты, песочницы, хуки, оркестрация, наблюдаемость — это и есть харнес. На Terminal Bench 2.0 команда подняла агента из-за пределов топ-30 в топ-5, поменяв только харнес, без смены модели.

🎭 **Дирижёр и оркестратор — две роли разработчика**
- Conductor (дирижёр) — в IDE, реальное время, каждая строка под контролем
- Orchestrator (оркестратор) — async, ставит цели, делегирует агентам, проверяет результат

⚠️ **Проблема 80%**
Агент пишет 80% кода за минуты, но оставшиеся 20% — граничные случаи, обработка ошибок, интеграция — требуют глубокого контекста. Ошибки выросли от синтаксических к концептуальным: код «выглядит правильно», но содержит незаметные архитектурные дефекты.

💰 **Экономика: низкий CapEx, высокий OpEx у вайб-кодинга**
Подписка на ИИ стоит копейки, но токены сжигаются в бесконечных промпт-петлях, а техдолг от неструктурированного кода копится экспоненциально. Агентная инженерия — высокий CapEx (спецификации, тесты, контекст), зато OpEx резко падает.

🏭 **Фабричная модель**
Разработчик проектирует не код, а систему, которая производит код. Как менеджер завода проектирует сборочную линию, а не собирает каждую деталь вручную.

**Практические рекомендации:**
- Заведите AGENTS.md (10 строк: стек, соглашения, жёсткие правила, воркфлоу)
- Пишите тесты и эвалы до генерации кода — это ваш контракт с ИИ
- Различайте прототипирование (вайб-кодинг) и продакшен (агентная инженерия) явно
- Инвестируйте в харнес как в общий актив команды
- ИИ умножает вашу инженерную культуру — и сильные, и слабые стороны

#ai #vibecoding #sdlc #google #dev #addyosmani
