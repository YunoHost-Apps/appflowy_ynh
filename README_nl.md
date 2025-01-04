# Package een app, uitgaand van dit voorbeeld

- Kopieer deze app voordat je er aan werkt, met de knop ['Gebruik dit template'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost)
- Bewerk `manifest.toml` met app-specifieke informatie
- Bewerk de scripts `install`, `upgrade`, `remove`, `backup` en `restore` , en alle overige relevante configuratiebestanden in `conf/`
  - Gebruik de [script helpers documentatie](https://yunohost.org/packaging_apps_helpers)
- Bewerk ook de `change_url` - en `config`-scripts, of verwijder ze als ze niet nodig zijn
- Voeg een `LICENSE`-bestand toe voor het pakket.
  - Voeg een `LICENSE`-bestand voor het pakket toe. NB: deze licentie is niet per se dezelfde als de licentie van de upstream app - het is enkel de licentie voor de code van het pakket en je bent vrij deze zelf te kiezen! (Mocht je niet weten welke te kiezen, wij bevelen [de AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt) aan)
- Bewerk bestanden in de map `doc/` ([zie de pagina over het documenteren van pakketten](https://yunohost.org/packaging_app_doc))
- De `README.md`-bestanden worden automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Example app voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/example)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/example)

[![Example app met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Example app snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

This is a dummy description of this app features


**Geleverde versie:** 1.0~ynh1

**Demo:** <https://demo.example.com>

## Schermafdrukken

![Schermafdrukken van Example app](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://example.com>
- Officiele gebruikersdocumentatie: <https://yunohost.org/apps>
- Officiele beheerdersdocumentatie: <https://yunohost.org/packaging_apps>
- Upstream app codedepot: <https://some.forge.com/example/example>
- YunoHost-store: <https://apps.yunohost.org/app/example>
- Meld een bug: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
of
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
