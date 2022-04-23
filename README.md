# web

[![Build Status](https://github.com/distbuild/web/workflows/CI/badge.svg?branch=main&event=push)](https://github.com/distbuild/web/actions?query=workflow%3ACI)
[![codecov](https://codecov.io/gh/distbuild/web/branch/main/graph/badge.svg?token=FS77A6KD37)](https://codecov.io/gh/distbuild/web)
[![License](https://img.shields.io/github/license/distbuild/web.svg)](https://github.com/distbuild/web/blob/main/LICENSE)
[![Tag](https://img.shields.io/github/tag/distbuild/web.svg)](https://github.com/distbuild/web/tags)
[![Gitter chat](https://badges.gitter.im/craftslab/distbuild.png)](https://gitter.im/craftslab/distbuild)



## Introduction

*web* is the web of [distbuild](https://github.com/distbuild) written in Vue.



## Prerequisites

- Vue >= 3.0



## Run

```bash
git clone https://github.com/distbuild/web.git

cd web
yarn && yarn run build
yarn run dev
```



## Docker

```bash
git clone https://github.com/distbuild/web.git

cd web
yarn && yarn run build
docker build --no-cache -f Dockerfile -t ghcr.io/distbuild/web:latest .
docker run ghcr.io/distbuild/web:latest
```



## License

Project License can be found [here](LICENSE).



## Reference
