# barscan-ai documentation!

## Description

Détection et classification automatique de codes-barres 1D/2D sur images à l’aide de YOLO et MLOps

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `az storage blob upload-batch -d` to recursively sync files in `data/` up to `a62/data/`.
* `make sync_data_down` will use `az storage blob upload-batch -d` to recursively sync files from `a62/data/` to `data/`.


