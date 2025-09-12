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

### Практика с репозиторием
- [ ] Клонировать общий учебный репозиторий.
- [ ] Создать ветку: `feature/<name>`.
- [ ] Добавить личный файл в `/participants/` с именем `vitaliy.md`.
- [ ] Закоммитить изменения.
- [ ] Запушить ветку и создать Pull Request.
- [ ] Попросить коллег о ревью (или смержить при настроенном нуле approvals).

### Индивидуальное задание (демо)
- [ ] Показать создание PR в UI и через `gh pr create`.
- [ ] Пояснить статусы, проверки, ревью, squash merge и удаление ветки.

### Чеклист завершения
- [ ] Файл `participants/vitaliy.md` вмержен в `main`.
- [ ] Выполнен полный цикл: clone → branch → commit → PR → merge.

