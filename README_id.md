# Memaket satu aplikasi, dimulai dari contoh ini

- Salin aplikasi ini sebelum mengerjakannya, menggunakan tombol ['Gunakan templat ini'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) di repo Github
- Edit `manifest.toml` dengan info khas aplikasi
- Edit skrip `install`, `upgrade`, `remove`, `backup` and `restore`, dan setiap berkas conf yang relevan dalam `conf/`
  - Menggunakan [dokumentasi pembantu skrip](https://yunohost.org/packaging_apps_helpers)
- Juga edit skrip `change_url` dan `config`, atau singkirkan mereka bila Anda sudah tidak memerlukannya
- Tambah berkas `LICENSE` pada paket.
  - NB: berkas `LICENSE` ini tidak dimaksudkan untuk selalu sama dengan aplikasi hulu - hanya LICENSE yang Anda inginkan untuk menerbitkan kode paket ini dan Anda bisa bebas memilihnya! (Bila Anda tidak tahu mana yang harus dipilih, kami sarankan [the AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt))
- Edit berkas di bawah direktori `doc/` ([lihat halaman mengenai mendokumentasikan paket](https://yunohost.org/packaging_app_doc))
- Berkas `README.md` akan dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Example app untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/example)](https://ci-apps.yunohost.org/ci/apps/example/)
![Status kerja](https://apps.yunohost.org/badge/state/example)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/example)

[![Pasang Example app dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Example app secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

This is a dummy description of this app features


**Versi terkirim:** 1.0~ynh1

**Demo:** <https://demo.example.com>

## Tangkapan Layar

![Tangkapan Layar pada Example app](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://example.com>
- Dokumentasi pengguna resmi: <https://yunohost.org/apps>
- Dokumentasi admin resmi: <https://yunohost.org/packaging_apps>
- Depot kode aplikasi hulu: <https://some.forge.com/example/example>
- Gudang YunoHost: <https://apps.yunohost.org/app/example>
- Laporkan bug: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
atau
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
