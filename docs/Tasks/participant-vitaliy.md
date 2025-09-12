## Задачи участника: Виталий

### Цель
Освоить базовую командную работу с репозиторием GitHub и показать Pull Request.

### Среда разработки (подготовка)
- [ ] Установлен Git, GitHub CLI, PNPM (через winget).
- [ ] Обновлён PATH (перезапуск терминала).
- [ ] Проверка версий: `git --version`, `gh --version`, `pnpm -v`.
- [ ] Включён Corepack и закреплён PNPM: `corepack enable`, `corepack prepare pnpm@9.6.0 --activate`.
- [ ] В `package.json` задано: `"packageManager": "pnpm@9.6.0"` (если есть файл).
- [ ] Git настроен: `git config --global user.name`, `user.email`, при необходимости `init.defaultBranch main`.
- [ ] Вход в GitHub CLI: `gh auth status` (должен быть logged in).

### Практика с репозиторием (одна ветка: main)
- [ ] Клонировать общий учебный репозиторий.
- [ ] Перейти в `main`: `git switch main && git pull`.
- [ ] Добавить личный файл в `/participants/` с именем `vitaliy.md`.
- [ ] Зафиксировать изменения: `git add . && git commit -m "Add vitaliy.md"`.
- [ ] Отправить в удалённый репозиторий: `git push`.

### Индивидуальное задание (демо)
- [ ] Показать PR как альтернативный процесс (для обсуждения), но в упражнении использовать прямые коммиты в `main`.
- [ ] Пояснить статусы, проверки, squash merge и удаление ветки (теория).

### Чеклист завершения
- [ ] Файл `participants/vitaliy.md` находится в `main` на GitHub.
- [ ] Выполнен цикл: clone → commit → push (без отдельных веток/PRs).
