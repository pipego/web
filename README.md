# web

[![Build Status](https://github.com/pipego/web/workflows/ci/badge.svg?branch=main&event=push)](https://github.com/pipego/web/actions?query=workflow%3Aci)
[![codecov](https://codecov.io/gh/pipego/web/branch/main/graph/badge.svg?token=FS77A6KD37)](https://codecov.io/gh/pipego/web)
[![License](https://img.shields.io/github/license/pipego/web.svg)](https://github.com/pipego/web/blob/main/LICENSE)
[![Tag](https://img.shields.io/github/tag/pipego/web.svg)](https://github.com/pipego/web/tags)
[![Gitter chat](https://badges.gitter.im/craftslab/pipego.png)](https://gitter.im/craftslab/pipego)



## Introduction

*web* is the web of [pipego](https://github.com/pipego) written in Vue.



## Prerequisites

- Vue >= 3.0



## Run

```bash
yarn
yarn build
yarn dev
```



## Docker

```bash
yarn && yarn run build
docker build --no-cache -f Dockerfile -t ghcr.io/pipego/web:latest .
docker run ghcr.io/pipego/web:latest
```



## License

Project License can be found [here](LICENSE).



## Reference
