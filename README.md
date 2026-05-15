# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Материалы

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip) — шаблон экосистемы

👉 [1C-Ecosystem.pdf](./1C-Ecosystem.pdf) — презентация для заказчиков и команды

Последний стабильный релиз (если выпущен):

👉 [Releases](https://github.com/d-n-komarov/1c-extension-ecosystem-dist/releases/latest)

## Версия

- Сборка: `latest`
- Коммит: `65d2fbb`
- Дата: `2026-05-15`

## Быстрый старт

1. Скачать ZIP и распаковать в папку проекта

2. Создать репозиторий на GitHub:
   - Открыть [github.com/new](https://github.com/new)
   - Repository name: например `my-1c-project`
   - Visibility: Private
   - **Не инициализировать** (без README, без .gitignore)
   - Нажать **Create repository**
   - Скопировать URL репозитория

3. Инициализировать git в распакованной папке:
   ```powershell
   git init
   git branch -m production
   git add .
   git commit -m "feat: init from 1c-extension-ecosystem template"
   git remote add origin https://github.com/<github-username>/<project-ecosystem-repo>.git
   git push -u origin production
   ```

4. Открыть проект в Claude — на выбор:

   **Claude CLI (PowerShell):** `cd <папка-проекта> && claude`

   **VS Code:** открыть папку проекта → перейти в чат Claude (расширение)

   Первое сообщение PM:
   ```
   Прочитай CLAUDE.md и начни инициализацию проекта.
   ```
   PM сам определит каталог, настроит пути и проведёт через все шаги.
