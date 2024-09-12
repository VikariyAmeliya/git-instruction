# Инструкция по работе с Git

## Основные команды

#### git init

#### git add <file>

#### git commit -m "Message"

#### git status

#### git log

#### git branch <branch-name>

#### git checkout <branch-name>

#### git merge <branch-name>

#### git push origin <branch-name>

#### git pull origin <branch-name>
```mermaid
HEAD -- это голова.
Коммит -- это всему голова.

```mermaid
graph LR;
    A[Git Basics] --> B[Хеши]
    A --> C[Лог]
    A --> D[HEAD]
    A --> E[Статусы файлов]
    A --> F[Оформление сообщений к коммитам]

    B --> B1[Хеш коммита: уникальный идентификатор]
    B --> B2[Функция SHA-1 для генерации хешей]

    C --> C1[git log: просмотр истории коммитов]
    C --> C2[Флаги: --oneline, --graph, --decorate]

    D --> D1[HEAD: текущий коммит]
    D --> D2[HEAD~1: родительский коммит]

    E --> E1[Untracked: файлы не отслеживаются]
    E --> E2[Unstaged: изменения не добавлены в индекс]
    E --> E3[Staged: изменения добавлены в индекс]

    F --> F1[Четкое описание изменений]
    F --> F2[Используйте им imperative mood (повелительное наклонение)]
    F --> F3[Ссылайтесь на задачи/проблемы при необходимости]
```
<и тут пустая строка!>

