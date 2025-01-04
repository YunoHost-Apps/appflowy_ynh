# Aplikazio bat paketatzen, honako adibidea oinarritzat hartuz

- Kopiatu aplikazio hau aldaketak egin baino lehen, Github gordailuko ['Erabili txantiloi hau'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) botoia erabiliz
- Editatu `manifest.toml` aplikazioaren informazio zehatzarekin
- Editatu `install`, `upgrade`, `remove`, `backup` eta `restore` scriptak, eta konfigurazio fitxategiak `conf/` direktorioan, beharrezkoak badira
  - Erabili [scripten laguntza-dokumentazioa](https://yunohost.org/packaging_apps_helpers)
- Editatu `change_url` eta `config` scriptak ere, edo kendu ez badute inolako betekizunik
- Gehitu `LICENSE` fitxategia paketerako.
  - Ohart ongi: `LICENSE` fitxategiak ez du zertan jatorrizko aplikazioaren lizentzia bera izan: pakete honen kodeak izatea nahi duzun lizentzia baino ez da eta aske zara berau aukeratzeko! (Ez badakizu zein aukeratu, guk [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt) gomendatzen dugu)
- Editatu `doc/` direktorioko fitxategiak ([ikus paketeak dokumentatzeari buruzko orria](https://yunohost.org/packaging_app_doc))
- `README.md` fitxategiak automatikoki sortuko dira <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker

---
<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Example app YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/example)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/example)

[![Instalatu Example app YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Example app YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This is a dummy description of this app features


**Paketatutako bertsioa:** 1.0~ynh1

**Demoa:** <https://demo.example.com>

## Pantaila-argazkiak

![Example app(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://example.com>
- Erabiltzaileen dokumentazio ofiziala: <https://yunohost.org/apps>
- Administratzaileen dokumentazio ofiziala: <https://yunohost.org/packaging_apps>
- Jatorrizko aplikazioaren kode-gordailua: <https://some.forge.com/example/example>
- YunoHost Denda: <https://apps.yunohost.org/app/example>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
edo
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
