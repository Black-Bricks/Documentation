# Android Документация

## Начало работы

Прежде чем начать разработку под Android, следует установить следующие инструменты, необходимые для создания приложения:

### Android Studio

Официальная IDE от Google. Скачать последнюю версию Android Studio можно с официально сайта. Запустить установочный файл и следовать инструкциям инсталлятора.

//TODO: links

### Homebrew

Homebrew - менеджер пакетов для Mac OS и Linux, который позволяет устанавливать тысячи пакетов, необходимых разработчику при помощи Terminal. Полная инструкция по установке доступна на официальном сайте. 

//TODO: links

### Git

Git - система контроля версий. Установка при помощи Homebrew выполняется следующими командами:

```bash
brew update
brew install git
```

Для проверки корректности установки рекомендуется запустить команду:

```bash
git --version
```

В итоге вы должны увидеть что-то вроде:

```bash
git version 2.30.1
```

### Cookiecutter???

Для быстрого создания проектов из шаблона используется Cookiecutter. 

//TODO: links

```bash
brew install cookiecutter
```

### //TODO: Cookiecutter or Android studio templates

//TODO: links to templates

//TODO: instalation instruction

### Fastlane

Экономие времени с помощью оптимизации релизов

Для его установки в систему есть несколько способов:

```bash
sudo gem install fastlane
// или через brew
brew cask install fastlane
```

О том, как настроить fastlane для использования на конкретном проекте компании, можно узнать в разделе **развёртывание(TBD link)**.

//TODO: links

## Архитектура

Конечной целью разработки любого программного обеспечения является создание продукта, построенного на максимально гибком, читабельном и легко обслуживаемом коде. В Android все эти качества обеспечиваются путем соблюдения соедующих принципов:

- DRY
- KISS
- YAGNI
- [SOLID](https://en.wikipedia.org/wiki/SOLID)
- Clean architecture
- MVVM architecture

### Основные концепции

TBD

### Слои приложения

TBD

### Внедрение зависимостей

TBD

### Структура директорий

TBD

### Использование шаблонов

TBD

## Code style

[Take from here](https://github.com/raywenderlich/kotlin-style-guide)
[and here](https://developer.android.com/kotlin/style-guide)
TBD

## Развертывание

TBD

## Best practice

TBD

## Usefull resources

TBD
