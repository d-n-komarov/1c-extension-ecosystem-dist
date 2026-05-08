# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Материалы

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip) — шаблон экосистемы

👉 [1C-Ecosystem.pdf](./1C-Ecosystem.pdf) — презентация для заказчиков и команды

Последний стабильный релиз (если выпущен):

👉 [Releases](https://github.com/d-n-komarov/1c-extension-ecosystem-dist/releases/latest)

## Версия

- Сборка: `latest`
- Коммит: `e99f6a7`
- Дата: `2026-05-08`

## Быстрый старт

1. Скачать ZIP и распаковать в папку проекта

2. Создать репозиторий на GitHub:
   - Открыть [github.com/new](https://github.com/new)
   - Repository name: например `1c-мой-проект`
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
   git remote add origin https://github.com/логин/мой-репозиторий.git
   git push -u origin production
   ```

4. Установить инструменты PM — открыть **PowerShell** из папки проекта:
   ```powershell
   cd <папка-проекта>
   powershell -ExecutionPolicy Bypass -File tools/get-tools.ps1
   ```

5. Открыть папку проекта в VS Code — следовать инструкциям в `CLAUDE.md`
