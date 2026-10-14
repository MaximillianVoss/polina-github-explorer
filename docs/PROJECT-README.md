# GitHub Repository Explorer · React + TypeScript

Учебные этапы из архива от 18.09.2026. Основная версия `src/` — завершённый Bonus с custom hook.

- [Исходное задание](materials/homework-2026-09-20/docs/frontend/github-explorer/ASSIGNMENT.md)
- [Инструкция с полными файлами каждого этапа](materials/homework-2026-09-20/docs/frontend/github-explorer/MANUAL.md)
- Проверки (исходная общая ссылка вне этого пакета)

## Запуск на Node.js 24

```bash
cd "/путь/к/комплекту/projects/frontend/github-explorer"
npm ci
npm run dev
```

## Учебные этапы без копирования поверх файлов

Все команды выполняются из корня `github-explorer`, где находится `package.json`.

| Команда | Версия |
| --- | --- |
| `npm run dev:step1` | Автозагрузка фиксированного react |
| `npm run dev:step2` | Пользовательский поиск по событию |
| `npm run dev:step3` | Поиск и локальный фильтр |
| `npm run dev` | Bonus: поиск вынесен в `useRepositories` |

Сначала остановите текущий сервер Ctrl+C, затем запустите другой этап. Проект и исходники не удаляются, ничего не переписывается.
Для одновременного запуска укажите разные порты, например `npm run dev:step1 -- --port 5174`.

```bash
npm test
npm run build
npm run build:stages
npm run preview
```

Последняя команда показывает production-сборку **Bonus**. Для этапа 1:
`npm run preview -- stages/step1` после `npm run build:stages`.

Данные публичные; не вставляйте токен GitHub в браузерный код. В условии требуются этапы, а не Git-ветки.

