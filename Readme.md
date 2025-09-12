Настройка данных для Git

1) Указать свои данные для каммитов
   Глобальные данные
```bash
git config --global user.name "Твоё Имя"
git config --global user.email "твоя@почта.com"
```
Данные на уровне проекта
```bash
cd /путь/к/репозиторию
git config user.name "Другое Имя"
git config user.email "другая@почта.com"
```
И проверьте заполнились ли данные
```bash
git config --list
```