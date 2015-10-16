<h1>TinyPNG</h1>

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url]

<h4>Notice: this is the folk of TinyPng, this just add feature for support multi level directory.</h4> 

<h2>Installation</h2>

<p>1. </p>
``` 
$ npm install -g node-tinypng
```
<p>2. </p>
Replace the tinypng.js, settings.json to your global node_modules path.
<p>3. </p>
``` 
$ tinypng -k I_KC7xGPxXfZPrEbrc-kXWBetAQ3G9rz (change this to your own api, tinypng have limit for 300/month.)
```


## Usage

```
Usage: tinypng [options] [image.png|*.png]
  -k, --api-key       Set default TinyPNG API key.
  -r, --allow-rewrite Rewrite the original files with compressed data.
  -n, --allow-nonpng  Allow you to compress files without .png extention.
  -p, --postfix       Postfix for compressed files when rewriting disabled.
  -h, --help          This message.
  -v, --version       Show version.
```

```
Example: tinypng -r image/*

```


## License

MIT © [Nikolay Solovyov](http://ozio.io)
