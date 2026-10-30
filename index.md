---
title: Документация Study Task Tracker
---

# Документация Study Task Tracker

Учебный проект по дисциплине «Программная инженерия».

## Содержание

- [Наша команда](Our-team.html)
- Предстоящие события
    - [События января](Предстоящие-события/События-Января.html)
    - [События февраля](Предстоящие-события/События-Февраля.html)

## О проекте

Приложение предназначено для учёта учебных задач,
сроков их выполнения и статуса готовности.

## Сценарий работы с приложением

Диаграмма показывает планируемую работу приложения.

<pre class="mermaid">
flowchart TD
    A[Открыть приложение] --> B[Посмотреть список задач]
    B --> C{Что нужно сделать?}
    C -->|Добавить задачу| D[Указать название, предмет и срок]
    D --> E[Сохранить задачу]
    E --> B
    C -->|Завершить задачу| F[Выбрать выполненную задачу]
    F --> G[Отметить как выполненную]
    G --> B
</pre>

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@12/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

## Ссылки

- [Репозиторий проекта](https://github.com/khalturing-study-labs/study-task-tracker)
- [Wiki проекта](https://github.com/khalturing-study-labs/study-task-tracker/wiki)
