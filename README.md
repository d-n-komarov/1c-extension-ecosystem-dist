# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Скачать

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip)

## Версия

- Сборка: `latest`
- Коммит: `4e2d826`
- Дата: `2026-05-05`

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
   git add .
   git commit -m "feat: init from 1c-extension-ecosystem template"
   git remote add origin https://github.com/логин/1c-ext-мой-проект.git
   git push -u origin production
   ```

4. Установить инструменты PM:
   ```powershell
   pwsh -ExecutionPolicy Bypass -File tools/get-tools.ps1
   ```

5. Открыть папку проекта в VS Code — следовать инструкциям в `CLAUDE.md`
