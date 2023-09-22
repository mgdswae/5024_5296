# Инструкция для работы с Git и удаленным репозиторием 

## Что такое Git?

Git - это система контроля версий. Или другими словами - хранилище, база данных истории разработки проекта. Такая система нужна для учета всех версий файла когда-либо созданных в проекте и содержащихся в Git (базе данных)

## Подготовка репозитория

Команда git init создает в ТЕКУЩЕМ каталоге новый локальный репозиторий (выполняется один раз):git init

## Добавляем игнорируемые файлы и каталоги

Прежде чем добавлять файлы в репозиторий нужно создать в корне репозитория файл .gitignore и записать туда игнорируемые файлы и каталоги. Для C# там надо написать # в каталогах bin и obj записываются скомпилированные файлы */bin/ */obj/ # в каталоге .vs хранятся локальные настройки VisualStudio .vs/# в каталоге packages хранятся в зависимости packages/
#### 5024_5296
