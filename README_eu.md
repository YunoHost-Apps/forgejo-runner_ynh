<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Forgejo Runner YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/forgejo-runner)](https://ci-apps.yunohost.org/ci/apps/forgejo-runner/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/forgejo-runner)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/forgejo-runner)

[![Instalatu Forgejo Runner YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=forgejo-runner)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Forgejo Runner YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Act runner is a runner for Gitea based on Gitea fork of act.

**Paketatutako bertsioa:** 3.0.3~ynh1

## Pantaila-argazkiak

![Forgejo Runner(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://forgejo.org/docs/next/admin/actions/#forgejo-runner>
- Jatorrizko aplikazioaren kode-gordailua: <https://code.forgejo.org/forgejo/runner>
- YunoHost Denda: <https://apps.yunohost.org/app/forgejo-runner>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/forgejo-runner_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/forgejo-runner_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/forgejo-runner_ynh/tree/testing --debug
edo
sudo yunohost app upgrade forgejo-runner -u https://github.com/YunoHost-Apps/forgejo-runner_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
