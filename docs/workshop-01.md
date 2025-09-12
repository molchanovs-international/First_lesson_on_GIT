## План семинара: ИИ разработка (пятница)

### Темы
- Что такое GitHub и зачем он нужен.
- Как подключиться к проекту (clone).
- Работа в ветках (branch, commit).
- Pull Request и review.
- Issues и README.

### Практика
- Каждый добавляет свой файл в общий репозиторий.

### Задания участникам
- Жарас: подготовить про GitHub и контроль версий.
- Полина: показать clone репозитория.
- Коля: объяснить branch + commit.
- Виталий: показать Pull Request.
- Катя: объяснить Issues и README.

### Учебный репозиторий
- Дайте аккаунты, дам доступ.
- Папка `/participants/` — каждый добавляет файл `имя.md`.

### Краткая инструкция (черновик README)
- Предусловия: установлен Git, аккаунт GitHub. (Опционально: установлен pnpm.)
- Клонирование и работа в ветке:
```bash
git clone https://github.com/molchanovs-international/First_lesson_on_GIT.git
cd First_lesson_on_GIT
git checkout -b feature/<your-name>
echo "# <your-name>" > participants/<your-name>.md
git add participants/<your-name>.md
git commit -m "Add <your-name>.md"
git push -u origin feature/<your-name>
```
- Создание Pull Request:
```bash
gh pr create --fill --base main --head feature/<your-name>
```
- Полный цикл: clone → branch → commit → PR → merge.


