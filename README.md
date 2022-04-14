# mlp-zygoat-plugins

# Usage

```sh
$ pip install --upgrade mlp-zygoat-plugins
```

Then, in `zygoat_settings.yml`, add the following:

```yml
exclude:
  - Backend__Dockerfile__Prod
  - Backend__Dockerfile__Local
extras:
  - mlp_zygoat_plugins.images:backend_images
```
