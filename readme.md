# Первое приложение на React [источник](https://ru.reactjs.org/)

## Набор инструментов React

React обладает рядом готовых инструментов для создания сайтов:

- **Create React App** - для создания одностраничных прилождений
- **Next.js** - для создания серверных сайтов на Node.js
- **Gatsby** - статический контент-ориентированный сайт
- **Neutrino**, **Parcel**, **Razzle** - для интеграции с существующей кодовой базой

[Более подробно](https://ru.reactjs.org/docs/create-a-new-react-app.html#more-flexible-toolchains)

Но можно и создать свой собственный набор JavaScript-инструментов с нуля. Так, сайт не будет перегружен лишним кодом и библиотеками. [Инструкция](https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658)

### Установка

1. Создать каталог для приложения
2. Выполнить инициализацию проекта (создается файл `package.json`) выполнив команду:

> npm init

3. Хорошая практика на данном этапе подключить git репозиторий.

> git init

Указав данные репозитория (например, github) в package.json:
```
"repository": {
    "type": "git",
    "url": "git+https://github.com/jamesscreen/react-001-hello.git"
},
"bugs": {
    "url": "https://github.com/jamesscreen/react-001-hello/issues"
},
"homepage": "https://github.com/jamesscreen/react-001-hello#readme"
```

```
git commit -m "add package.json"
git remote add origin https://github.com/jamesscreen/react-001-hello.git
git push -u origin master
```

4. Создать в папке проекта две директории:

    - public
    - src

