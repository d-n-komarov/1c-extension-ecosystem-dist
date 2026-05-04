# 1C Extension Ecosystem — Distribution

Публичный дистрибутив шаблона экосистемы разработки расширений 1С:Предприятие 8.3.

## Скачать

👉 [1c-extension-ecosystem.zip](./1c-extension-ecosystem.zip)

## Версия

- Сборка: `latest`
- Коммит: `16e50a7`
- Дата: `2026-05-04`

## Быстрый старт

1. Скачать ZIP
2. Распаковать в папку проекта
3. Инициализировать git:
   ```powershell
   git init
   git add .
   git commit -m "feat: init from 1c-extension-ecosystem template"
   git remote add origin <url-вашего-репозитория>
   git push -u origin main
   ```
4. Установить инструменты PM:
   ```powershell
   pwsh -ExecutionPolicy Bypass -File tools/get-tools.ps1
   ```
5. Открыть в VS Code — следовать инструкциям в `CLAUDE.md`

## Состав шаблона

- `CLAUDE.md` — контекст и инструкции для Claude Code (PM-роль)
- `GOALS.md`, `TODO.md`, `ADR.md`, `STATUS.md`, `CHANGELOG.md`, `KNOWLEDGE.md`
- `src/` — структура проекта 1C: Platform Tools
- `tools/get-tools.ps1` — автоустановка портативных инструментов
- `scripts/ai_review.py` — AI review для CI/CD
- `.github/`, `.gitlab-ci.yml` — CI/CD конфигурации
- `.mcp.json` — MCP серверы для Claude Code
