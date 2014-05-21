# winston-kibana
[![Build Status](https://travis-ci.org/lemonde/winston-kibana.svg?branch=master)](https://travis-ci.org/lemonde/winston-kibana)
[![Dependency Status](https://david-dm.org/lemonde/winston-kibana.svg?theme=shields.io)](https://david-dm.org/lemonde/winston-kibana)
[![devDependency Status](https://david-dm.org/lemonde/winston-kibana/dev-status.svg?theme=shields.io)](https://david-dm.org/lemonde/winston-kibana#info=devDependencies)

Winston rewriter to optimized logs for Kibana usage.

## Install

```
npm install winston-kibana
```

## Usage

```js
var winston = require('winston');
var winstonKibana = require('winston-kibana');

winston.addRewriter(winstonKibana({application: 'my-application'}));
```

## License

MIT