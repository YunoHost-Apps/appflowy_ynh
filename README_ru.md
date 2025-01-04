# Пакетирование приложения, начиная с этого примера

- Скопируйте приложение перед тем, как работать над ним, используя кнопку ['Use this template'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) на GitHub-репозитории
- Отредактируйте `manifest.toml`, добавив данные приложения
- Отредактируйте скрипты `install`, `upgrade`, `remove`, `backup` and `restore`, и добавьте необходимые файлы конфигурации в `conf/`
  - Используя [документацию по помощникам скриптов](https://yunohost.org/packaging_apps_helpers)
- Также отредактируйте скрипты `change_url` and `config`, или удалите их, если Вы их не используете
- Добавьте файл `LICENSE` в пакет.
  - Важно: этот файл `LICENSE` не обязан быть таким же, как и в главной ветке приложения - это только лицензия, под которой Вы хотите распространять код данного пакета. (если Вы не знаете, какую выбрать лицензию, мы рекомендуем [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt))
- Отредактируйте файлы в директории `doc/` ([смотрите страницу о документировании пакетов](https://yunohost.org/packaging_app_doc))
- Файлы `README.md` автоматически генерируются <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Example app для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Состояние работы](https://apps.yunohost.org/badge/state/example)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/example)

[![Установите Example app с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Example app быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

This is a dummy description of this app features


**Поставляемая версия:** 1.0~ynh1

**Демо-версия:** <https://demo.example.com>

## Снимки экрана

![Снимок экрана Example app](./doc/screenshots/example.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://example.com>
- Официальная документация пользователя: <https://yunohost.org/apps>
- Официальная документация администратора: <https://yunohost.org/packaging_apps>
- Репозиторий кода главной ветки приложения: <https://some.forge.com/example/example>
- Магазин YunoHost: <https://apps.yunohost.org/app/example>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
или
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
