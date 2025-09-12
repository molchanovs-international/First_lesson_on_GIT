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

### Практика с репозиторием (одна ветка: main)
- [ ] Клонировать общий учебный репозиторий.
- [ ] Перейти в `main`: `git switch main && git pull`.
- [ ] Добавить личный файл в `/participants/` с именем `kolya.md`.
- [ ] Зафиксировать изменения: `git add . && git commit -m "Add kolya.md"`.
- [ ] Отправить в удалённый репозиторий: `git push`.

### Индивидуальное задание (объяснение)
- [ ] Объяснить, зачем нужны ветки в реальных проектах, но практику выполнить без веток.
- [ ] Показать `git add`, `git commit -m`, атомарность коммитов и хорошие сообщения.

### Чеклист завершения
- [ ] Файл `participants/kolya.md` находится в `main` на GitHub.
- [ ] Выполнен цикл: clone → commit → push (без отдельных веток/PRs).


Новые изменения в файле
