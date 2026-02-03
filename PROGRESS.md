# Progress Tracker - Mini-Issues

Этот файл отслеживает прогресс разработки Budget Buddy CLI. Каждый коммит соответствует одной mini-issue.

## Как вести

- Каждая строка таблицы = один коммит
- ID: P-001, P-002, ... (последовательно, без пропусков)
- Date: дата коммита в формате YYYY-MM-DD
- Title: точное сообщение коммита
- Acceptance criteria: 2-4 проверяемых пункта (можно проверить вручную или автоматически)
- Files changed: фактические файлы/папки, которые изменились в коммите
- Status: ✅ Done (после коммита и push)
- Notes: краткое объяснение "зачем это нужно" (1 строка)

## Примеры Acceptance Criteria

- ✅ "Создан файл X с функциями Y и Z"
- ✅ "Добавлены тесты для функции X, покрытие >80%"
- ✅ "Обновлена документация в handbook/X.md с примерами"
- ✅ "CI настроен для запуска проверок qa/check_X.py"

## Формат таблицы

Таблица обновляется перед каждым коммитом. Новая строка добавляется вверху (под заголовком), чтобы последние задачи были видны первыми.

## Mini-Issues

| ID | Date | Title | Acceptance criteria | Files changed | Status | Notes |
|----|------|-------|---------------------|---------------|--------|-------|
| P-005 | 2026-02-03 | Docs: add roadmap for 100 commits | 1) handbook/ROADMAP.md создан 2) Этапы MVP → reports → QA → tests → polish описаны 3) PROGRESS обновлён | handbook/ROADMAP.md, PROGRESS.md | ✅ Done | План этапов разработки |
| P-004 | 2026-02-03 | Docs: add PROJECT_CHARTER | 1) handbook/PROJECT_CHARTER.md создан 2) Есть миссия, принципы, scope и non-scope 3) PROGRESS.md обновлён | handbook/PROJECT_CHARTER.md, PROGRESS.md | ✅ Done | Фиксация миссии и границ проекта |
| P-003 | 2026-02-03 | Docs: add PROGRESS mini-issue tracker | 1) PROGRESS.md содержит таблицу с примерами 2) Добавлены пояснения "как вести" с примерами acceptance criteria 3) Описан формат таблицы и правила обновления | PROGRESS.md | ✅ Done | Улучшение документации трекера прогресса для ясности |
| P-002 | 2026-02-03 | Docs: add README with project vision and usage | 1) README содержит цель проекта и кому полезно 2) Есть быстрый старт 3) Указаны ограничения (только stdlib) 4) Описана структура репозитория | README.md, PROGRESS.md | ✅ Done | Основная документация проекта для новых пользователей |
| P-001 | 2026-02-03 | Chore: init repo structure for budget buddy | 1) Созданы папки app/, handbook/, spec/, qa/, tests/, examples/ 2) Добавлены .gitkeep где нужно 3) PROGRESS.md создан с таблицей | app/, handbook/, spec/, qa/, tests/, examples/, PROGRESS.md | ✅ Done | Инициализация структуры проекта для Budget Buddy CLI |
