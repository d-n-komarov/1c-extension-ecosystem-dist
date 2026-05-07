# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Скачать

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip)

## Версия

- Сборка: `latest`
- Коммит: `a797326`
- Дата: `2026-05-07`

## Быстрый старт

1. Скачать ZIP и распаковать в папку проекта

2. Создать репозиторий на GitHub:
   - Открыть [github.com/new](https://github.com/new)
   - Repository name: например 
   - Visibility: Private
   - **Не инициализировать** (без README, без .gitignore)
   - Нажать **Create repository**
   - Скопировать URL репозитория (напр. )

3. Инициализировать git в распакованной папке:
   ```powershell
   git init
   git branch -m production
   git add .
   git commit -m "feat: init from 1c-extension-ecosystem template"
   git remote add origin https://github.com/логин/мой-репозиторий.git
   git push -u origin production
   ```

4. Установить инструменты PM — открыть **PowerShell** и выполнить из папки проекта:
   ```powershell
   cd <папка-проекта>

   # PowerShell 7+ (pwsh):
   pwsh -ExecutionPolicy Bypass -File tools/get-tools.ps1

   # PowerShell 5 (встроен в Windows 10):
   powershell -ExecutionPolicy Bypass -File tools/get-tools.ps1
   ```
   Если не знаете версию — попробуйте первый вариант, при ошибке используйте второй.

5. Открыть папку проекта в VS Code — следовать инструкциям в `CLAUDE.md`
