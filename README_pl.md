# Pakowanie aplikacji, zaczynając od tego przykładu

- Skopiuj tę aplikację zanim rozpoczniesz nad nią pracę używając przycisku ['Użyj tego szablonu'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) na GitHubie
- Edytuj `manifest.toml` z informacjami o danej aplikacji
- Edytuj skrypty `install`, `upgrade`, `remove`, `backup` i `restore` i inne powiązane pliki w `conf/`
  - Używa [dokumentacji do skryptów pomocniczych](https://yunohost.org/packaging_apps_helpers)
- Edytuj również skrypty `change_url` i `config` lub usuń je, jeśli nie są Ci potrzebne
- Dodaj plik `LICENSE` dla paczki.
  - UWAGA: plik `LICENSE` niekoniecznie musi być tą samą LICENCJĄ, co aplikacja źródłowa — jest to po prostu LICENCJA, z którą chcesz opublikować kod tego pakietu, i możesz ją wybrać swobodnie! (Jeśli nie wiesz, którą wybrać, zalecamy [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt))
- Edytuj pliki w katalogu `doc/` ([zobacz stronę o dokumentowaniu pakietów](https://yunohost.org/packaging_app_doc))
- Pliki `README.md` są automatycznie generowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Example app dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Status działania](https://apps.yunohost.org/badge/state/example)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/example)

[![Zainstaluj Example app z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Example app na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

This is a dummy description of this app features


**Dostarczona wersja:** 1.0~ynh1

**Demo:** <https://demo.example.com>

## Zrzuty ekranu

![Zrzut ekranu z Example app](./doc/screenshots/example.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://example.com>
- Oficjalna dokumentacja: <https://yunohost.org/apps>
- Oficjalna dokumentacja dla administratora: <https://yunohost.org/packaging_apps>
- Repozytorium z kodem źródłowym: <https://some.forge.com/example/example>
- Sklep YunoHost: <https://apps.yunohost.org/app/example>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
lub
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
