# ngx-renuo-upload

This is a component for the renuo upload (<https://github.com/renuo/renuo-upload>)

[![Code Climate](https://codeclimate.com/github/renuo/ngx-renuo-upload.png)](https://codeclimate.com/github/renuo/ngx-renuo-upload)
[![Build Status](https://travis-ci.org/renuo/ngx-renuo-upload.svg?branch=master)](https://travis-ci.org/renuo/ngx-renuo-upload)
[![Build Status](https://travis-ci.org/renuo/ngx-renuo-upload.svg?branch=develop)](https://travis-ci.org/renuo/ngx-renuo-upload)
[![Build Status](https://travis-ci.org/renuo/ngx-renuo-upload.svg?branch=testing)](https://travis-ci.org/renuo/ngx-renuo-upload)

## Important Links

* <https://github.com/renuo/ngx-renuo-upload>
* <https://upload-demo.renuoapp.ch>
* <https://upload-demo-develop.renuoapp.ch>

## How to use

### Single Upload Component

![simple-upload](https://cloud.githubusercontent.com/assets/20790833/26151729/54d950c2-3b04-11e7-83b0-cee18cb44a32.gif)

[read more](documentation/SINGLEUPLOAD.md)

### Multi Upload Component

![multi-upload](https://cloud.githubusercontent.com/assets/20790833/26152934/7f5a86ae-3b09-11e7-8c1e-7a136d062fa2.gif)

[read more](documentation/MULTIUPLOAD.md)

### Single Image

![image-with-filter](https://cloud.githubusercontent.com/assets/20790833/26243895/c27e84d2-3c8d-11e7-88c2-a0834e012ab1.png)

[read more](documentation/IMAGE.md)

### Gallery

![gallery](https://cloud.githubusercontent.com/assets/20790833/26243783/5d34cdfc-3c8d-11e7-8888-4165bd674983.png)

[read more](documentation/GALLERY.md)

## Developing

### Setup

```sh
git clone git@github.com:renuo/ngx-renuo-upload.git
cd ngx-renuo-upload
bin/setup
```

#### Configuration

```sh
bin/setup
```

### Deployment (Demo Page)

The deployment of the demo page will run automatically on Firebase with Travis.

#### Demo Pages

* <https://upload-demo.renuoapp.ch>
* <https://upload-demo-develop.renuoapp.ch>

#### Manual Deployment

```sh
yarn build
firebase deploy
```

See <https://firebase.google.com/docs/cli/>

### Tests

```sh
bin/check
```

This runs

* keyword check (console.log, ...)
* scss-lint
* tslint
* sorts translations

To develop TDD and restart tests after each change run:

```sh
bin/tdd
```

#### Coverage

To show the graphical coverage report run:

```sh
bin/coverage
```

### bin-scripts

* `bin/check`: runs all checks
* `bin/check-server-start`: subscript of `bin/check` to test if server runs
* `bin/coverage`: shows coverage report
* `bin/fix` runs auto-corrections (`tslint --fix`)
* `bin/generate-i18n`: generate new translation keys
* `bin/prettify-translations`: sorts the translation keys
* `bin/setup`: sets up the project
* `bin/run`: runs a local instance of the server

### Run server

```sh
bin/run
```

### Maintenance

To update dependencies it's best to use:

```sh
yarn upgrade-interactive
```

## Problems

If there are problems with the project, feel free to contact Pascal Andermatt.

![Pascal Andermatt](https://s.gravatar.com/avatar/1ee132b4d89f7d2e82db5717eefdcd86?s=80)

## Copyright

Coypright 2017 [Renuo AG](https://www.renuo.ch/).

### MIT License

See [LICENSE](LICENSE) file.
