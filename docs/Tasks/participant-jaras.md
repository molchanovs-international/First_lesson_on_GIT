## Задачи участника: Жарас

### Цель
Освоить базовую командную работу с репозиторием GitHub и подготовить мини-доклад про GitHub и контроль версий.

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
- [ ] Добавить личный файл в `/participants/` с именем `jaras.md`.
- [ ] Зафиксировать изменения: `git add . && git commit -m "Add jaras.md"`.
- [ ] Отправить в удалённый репозиторий: `git push`.

### Индивидуальное задание (доклад)
- [ ] Подготовить объяснение: что такое GitHub, зачем контроль версий, ключевые преимущества для команды.
- [ ] Кратко показать: репозитории, ветки, PR, Issues, Actions (по желанию).

### Чеклист завершения
- [ ] Файл `participants/jaras.md` находится в `main` на GitHub.
- [ ] Выполнен цикл: clone → commit → push (без отдельных веток/PRs).


