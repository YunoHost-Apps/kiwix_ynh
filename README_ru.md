<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Kiwix для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/kiwix.svg)](https://ci-apps.yunohost.org/ci/apps/kiwix/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Установите Kiwix с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Kiwix быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Поставляемая версия:** 3.6.0~ynh3

**Демо-версия:** <http://library.kiwix.org/>

## Снимки экрана

![Снимок экрана Kiwix](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.kiwix.org/>
- Официальная документация администратора: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Репозиторий кода главной ветки приложения: <https://github.com/kiwix/kiwix-tools>
- Магазин YunoHost: <https://apps.yunohost.org/app/kiwix>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
или
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
