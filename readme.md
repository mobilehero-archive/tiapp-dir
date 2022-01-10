[//]: # (header-start)

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
<h1 align="center">
	Axway Amplify End-of-Life Announcement
</h1>
<h2 align="center">
	👇 &nbsp; See notes below  &nbsp; 👇
</h2>	
</a>

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Cloud Services (2012 - 2022)
	</p>
</a>
<hr>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h4 align="center">
🛑 &nbsp;&nbsp; All products affected by the announcements will not be supported by Axway effective their EOL dates in 2022.
</h4>

<h4 align="center">
Some Open-Source versions of Axway products will live on after End-of-Life (EOL) Axway Amplify product announcements.  However, some products are closed-source and will NOT continue after the shut down in 2022.  
	</h4>
</a>
<p>&nbsp;</p>

> 👉 &nbsp;&nbsp; Stay tuned for more info as plans are being made to save the Titanium project and move it under the control of a independent group of developers.

<p>&nbsp;</p>
<hr>
<p>&nbsp;</p>
<p>&nbsp;</p>

[//]: # (header-end)

# tiapp-dir 

[![tiapp-dir version](https://img.shields.io/npm/v/tiapp-dir.png)](https://www.npmjs.com/package/tiapp-dir)
[![tiapp-dir downloads](https://img.shields.io/npm/dm/tiapp-dir.svg)](https://www.npmjs.com/package/tiapp-dir)
[![tiapp-dir dependencies](https://img.shields.io/librariesio/release/npm/tiapp-dir.svg)](https://www.npmjs.com/package/tiapp-dir)

Find the root directory of an appcelerator titanium project
 
> (based on https://github.com/sindresorhus/pkg-dir)
 


## Install

```
$ npm install --save tiapp-dir
```

## Install [![NPM version](https://badge.fury.io/js/tiapp-dir.svg)](https://www.npmjs.com/package/tiapp-dir)


```bash
$ npm install--save tiapp-dir
```

## Usage

```
/
└── projects
    └── appcelerator
        └── mobilehero-demo
            ├── package.json
            ├── tiapp.xml
            └── foo
                ├── aaa.js
                ├── package.json
                └── bar
                    ├── bbb.js
                    ├── ccc.js
                    └── example.js
```

```js
// example.js
var tiappDir = require('tiapp-dir');

tiappDir(__dirname).then(function (rootPath) {
	console.log(rootPath);
	//=> '/projects/appcelerator/mobilehero-demo'
});
```


## API

### tiappDir([cwd])

Returns a promise that resolves to the project root path or `null`.

### tiappDir.sync([cwd])

Returns the project root path or `null`.

#### cwd

Type: `string`  
Default: `process.cwd()`

Directory to start from.


## Related

- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - Find the root directory of a npm package
- [pkg-up](https://github.com/sindresorhus/pkg-up) - Find the closest package.json file
- [find-up](https://github.com/sindresorhus/find-up) - Find a file by walking up parent directories


## License

```
The MIT License (MIT)

Copyright (c) 2016 Superhero Studios Incorporated

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
