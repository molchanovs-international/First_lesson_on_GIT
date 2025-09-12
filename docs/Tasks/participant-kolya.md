## Задачи участника: Коля

### Цель
Освоить базовую командную работу с репозиторием GitHub и объяснить `branch` и `commit`.

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
- [ ] Добавить личный файл в `/participants/` с именем `kolya.md`.
- [ ] Закоммитить изменения.
- [ ] Запушить ветку и создать Pull Request.
- [ ] Дождаться ревью/мержа или смержить при разрешённых настройках.

### Индивидуальное задание (объяснение)
- [ ] Объяснить, зачем нужны ветки, отличия `main` vs feature-ветка, изоляция работы.
- [ ] Показать `git add`, `git commit -m`, атомарность коммитов и хорошие сообщения.

### Чеклист завершения
- [ ] Файл `participants/kolya.md` вмержен в `main`.
- [ ] Выполнен полный цикл: clone → branch → commit → PR → merge.

