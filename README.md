# Cloud Init
[![CircleCI build status](https://circleci.com/gh/canonical-web-and-design/cloud-init.io.svg?style=shield)](https://circleci.com/gh/canonical-web-and-design/cloud-init.io) [![Code coverage](https://codecov.io/gh/canonical-web-and-design/cloud-init.io/branch/master/graph/badge.svg)](https://codecov.io/gh/canonical-web-and-design/cloud-init.io)

Codebase for http://cloud-init.io - the marketing website

## Local development

The simplest way to run the site locally is to first [install Docker](https://docs.docker.com/engine/installation/) (on Linux you may need to [add your user to the `docker` group](https://docs.docker.com/engine/installation/linux/linux-postinstall/)), and then use the `./run` script:

``` bash
./run
```

Once the containers are setup, you can visit <http://127.0.0.1:8009> in your browser.

### Building CSS

For working on [Sass files](_sass), you may want to dynamically watch for changes to rebuild the CSS whenever something changes.

To setup the watcher, open a new terminal window and run:

``` bash
./run watch
```

## Licence

Code licensed [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd.](http://www.canonical.com/).

With ♥ from Canonical
