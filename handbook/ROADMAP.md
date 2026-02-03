# Roadmap — этапы до 100 коммитов

## Этап 1: MVP (фундамент и базовый CLI)

- Структура репозитория, README, PROGRESS, charter.
- Лицензия, CODE_OF_CONDUCT, SECURITY, SUPPORT.
- Конфиги: .editorconfig, .gitattributes, .gitignore.
- Шаблоны: issue, PR, CONTRIBUTING, STYLE_GUIDE.
- Spec: схема данных, команды CLI, коды ошибок, типы отчётов.
- Quickstart в handbook.

## Этап 2: Ядро приложения

- Скелет app: entrypoint, config, storage (JSON), models.
- Команды: init, add (income/expense), list, categories, delete, edit.

## Этап 3: Отчёты

- Движок отчётов, summary, by-category, monthly.
- Документация по отчётам.

## Этап 4: Импорт/экспорт и примеры

- Экспорт/импорт CSV.
- Примеры: sample_data.json, sample_import.csv, гайд.

## Этап 5: QA и CI

- QA-скрипты: ссылки, markdown, валидация данных, smoke CLI.
- CI: workflow, подключение проверок, step summary.

## Этап 6: Тесты

- Каркас unittest, прогон в CI.
- Тесты: storage, models, add/list, edit/delete, categories, отчёты, CSV.

## Этап 7: Полировка и расширение

- Улучшение ошибок, флаг --data, парсинг дат и сумм, поиск.
- Бюджеты и отчёт budget-status.
- Красивый вывод таблиц, --json, automation/backup гайды.
- Dependabot, workflow_dispatch, troubleshooting, glossary, FAQ.
- Расширенные отчёты: cashflow, recurring, net worth.
- Целостность данных, QA и CI для проверок.
- Buddy coach, release/changelog, финальная согласованность.
