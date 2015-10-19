<h1>TinyPNG</h1>


<h4>Using tinypng to batch compress your png images, support multi level directory.</h4>

<h2>Installation</h2>

<p>1. Package init:</p>
``` 
$ npm install -g node-tinypng
```
<p>2. Replace the tinypng.js, settings.json to your global node_modules path.</p>

<p>3. Change api:</p>
``` 
$ tinypng -k I_KC7xGPxXfZPrEbrc-kXWBetAQ323rz
```
hint: change the above api to your owns. Get api: https://tinypng.com/developers (free 500 images/month. )


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
this is the folk from https://github.com/ozio/tinypng, this folk just add the feature to support multi level directory.