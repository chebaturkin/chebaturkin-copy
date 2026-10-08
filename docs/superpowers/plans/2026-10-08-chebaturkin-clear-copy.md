# Chebaturkin Clear Copy Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** собрать отдельный публичный репозиторий со скиллом `chebaturkin-clear-copy` и опубликовать его в GitHub.

**Architecture:** пакет состоит из `SKILL.md`, справочника студии и интерфейсных метаданных. README объясняет назначение и установку, не дублируя правила скилла.

**Tech Stack:** Markdown, YAML, Git, GitHub CLI.

---

### Task 1: Собрать пакет скилла

**Files:**
- Create: `SKILL.md`
- Create: `references/studio-guide.md`
- Create: `agents/openai.yaml`
- Create: `README.md`

- [ ] Перенести текущие инструкции и справочник.
- [ ] Удалить служебные разделы о происхождении подхода и внешних материалах.
- [ ] Обновить отображаемое имя на `Chebaturkin Clear Copy`.
- [ ] Добавить краткое описание состава и установки в `README.md`.

### Task 2: Проверить пакет

**Files:**
- Check: `SKILL.md`
- Check: `references/studio-guide.md`
- Check: `agents/openai.yaml`

- [ ] Запустить `quick_validate.py` для папки скилла.
- [ ] Поискать запрещённые имена, ссылки и упоминания внешних материалов.
- [ ] Проверить, что YAML и Markdown читаются без незавершённых заготовок.

### Task 3: Опубликовать репозиторий

**Files:**
- Create: `.git/`

- [ ] Создать локальный git-репозиторий и первый коммит.
- [ ] Создать публичный репозиторий `chebaturkin/chebaturkin-clear-copy`.
- [ ] Отправить ветку `main` и проверить опубликованный URL.
