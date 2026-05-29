# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Материалы

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip) — шаблон экосистемы

👉 [1C-Ecosystem.pdf](./1C-Ecosystem.pdf) — презентация для заказчиков и команды

Последний стабильный релиз (если выпущен):

👉 [Releases](https://github.com/d-n-komarov/1c-extension-ecosystem-dist/releases/latest)

## Версия

- Сборка: `latest`
- Коммит: `861a2bc`
- Дата: `2026-05-29`

## Быстрый старт

1. Скачать ZIP и распаковать в папку проекта

2. (Опционально) Подключить к git-хостингу:
   ```powershell
   git init
   git branch -m production
   git add .
   git commit -m "feat: init from 1c-extension-ecosystem template"
   git remote add origin <url-репозитория>
   git push -u origin production
   ```

3. Открыть проект в Claude — на выбор:

   **Claude CLI (PowerShell):** `cd <папка-проекта> && claude`

   **VS Code:** открыть папку проекта → перейти в чат Claude (расширение)

   Первое сообщение PM:
   ```
   Прочитай CLAUDE.md и начни инициализацию проекта.
   ```
   PM сам определит каталог, настроит пути и проведёт через все шаги.
