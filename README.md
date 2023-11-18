# Flexberry.LaboratornyeRabotyInformacionnayaBezopasnost
Репозиторий создан с помощью Flexberry Designer (https://designer.flexberry.net)

## Развернутое приложение на GitHub Pages

Демо-приложение с БД IndexedDb (в браузере):
https://flexberry-app-sandbox.github.io/Flexberry.LaboratornyeRabotyInformacionnayaBezopasnost/

## Запуск приложения в Docker

Для запуска приложения с БД требуется [Docker](https://docker.com).

Последовательность действий:

1. Собрать Docker-образы
```
\src\Docker> .\create-image.cmd
```

2. Запустить Docker-образы
```
\src\Docker> .\start.cmd
```

Приложение будет доступно по адресу http://localhost

3. Остановить выполнение Docker-образов
```
\src\Docker> .\stop.cmd
```

## Ссылки на документацию

Подробнее о сгенерированном фронтенде: https://flexberry.github.io/ru/ef3_landing_page.html  
Подробнее о сгенерированном бекенде: https://flexberry.github.io/ru/fo_orm-odata-service.html
