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

#### HEAD -- это голова.
#### Коммит -- это всему голова.

```mermaid
graph TD
    A[Git Basics] --> B[Хеши]
    A --> C[Лог]
    A --> D[HEAD]
    A --> E[Статусы]
    A --> F[Коммиты]

    B --> B1[Хеш: уник. ID]
    B --> B2[SHA-1: алгоритм]

    C --> C1[git log: история]
    C --> C2[Флаги: --oneline, --graph]

    D --> D1[HEAD: текущий коммит]
    D --> D2[HEAD~1: родительский]

    E --> E1[Untracked: не отслеж.]
    E --> E2[Unstaged: не добав.]
    E --> E3[Staged: добавлен.]

    F --> F1[Краткое описание]
    F --> F2[Императивный стиль]
    F --> F3[Ссылка на задачи]


```
<и тут пустая строка!>


