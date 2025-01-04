# Armar una aplicación empezando por este ejemplo

- Copia esta aplicación antes se trabajar en ella,utilizando el botón ['use esta plantilla'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) en el repositorio de Github
- Edita el archivo `manifest.toml` con las informaciones especifica de la aplicación
- Edita los archivos de scripts `install`, `upgrade`, `remove`, `backup`, `restore` y los archivos de configuraciones ubicados en `conf/`
  - Usando la [documentación des los scripts helpers](https://yunohost.org/packaging_apps_helpers)
- Edita el archivo de script `change_url` and `config` o borra los si no les son utiles
- Agrega un archivo `LICENSE` para el paquete.
  - No es necesario que la `LICENSE` de los script de gestion de aplicacion sea la misma que la LICENSE de la aplicacion gestionada. Recomendamos usar [the AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt)
- Edita los archivos en el directorio`doc/` ([más informaciones](https://yunohost.org/packaging_app_doc))
- Los archivos`README.md`estan generados automáticamente <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Example app para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Estado funcional](https://apps.yunohost.org/badge/state/example)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/example)

[![Instalar Example app con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarExample app rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

This is a dummy description of this app features


**Versión actual:** 1.0~ynh1

**Demo:** <https://demo.example.com>

## Capturas

![Captura de Example app](./doc/screenshots/example.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://example.com>
- Documentación usuario oficial: <https://yunohost.org/apps>
- Documentación administrador oficial: <https://yunohost.org/packaging_apps>
- Repositorio del código fuente oficial de la aplicación : <https://some.forge.com/example/example>
- Catálogo YunoHost: <https://apps.yunohost.org/app/example>
- Reportar un error: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
o
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
