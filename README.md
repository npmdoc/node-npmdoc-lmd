# api documentation for  [lmd (v1.13.4)](http://lmdjs.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-lmd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lmd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lmd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lmd)
#### LMD: Lazy Module Declaration

[![NPM](https://nodei.co/npm/lmd.png?downloads=true)](https://www.npmjs.com/package/lmd)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lmd/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-lmd_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lmd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lmd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lmd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikhail Davydov",
        "email": "i@azproduction.ru"
    },
    "bin": {
        "lmd": "./bin/lmd"
    },
    "bugs": {
        "url": "https://github.com/azproduction/lmd/issues"
    },
    "contributors": [
        {
            "name": "Mikhail Davydov",
            "email": "i@azproduction.ru",
            "url": "http://azproduction.ru/"
        },
        {
            "name": "texnikru",
            "url": "https://github.com/texnikru"
        },
        {
            "name": "Leonid Borisenko",
            "url": "https://github.com/leonidborisenko"
        },
        {
            "name": "Ivan ant-hill",
            "url": "https://github.com/ant-hill"
        },
        {
            "name": "Jonathan Dumaine",
            "email": "jonathan.dumaine@dumstruck.com",
            "url": "http://www.jonathan-dumaine.com/"
        },
        {
            "name": "Alexander Myadzel",
            "email": "myadzel@gmail.com",
            "url": "http://twitter.com/thenameisbusy"
        },
        {
            "name": "Maxceem",
            "url": "https://github.com/Maxceem"
        },
        {
            "name": "Denis Chistyakov",
            "email": "den.chistyakov@gmail.com",
            "url": "http://disachist.ya.ru"
        },
        {
            "name": "alnikitich",
            "url": "https://github.com/alnikitich"
        },
        {
            "name": "Egor Halimonenko",
            "email": "1+github@h123.ru",
            "url": "http://h123.ru"
        },
        {
            "name": "kastigar",
            "url": "https://github.com/kastigar"
        },
        {
            "name": "Vadim Budarin",
            "email": "budarin-vv@yandex.ru"
        },
        {
            "name": "Evgeniy Solodukhin",
            "email": "evgeniy@solodukhin.ru"
        },
        {
            "name": "Alexey Ivanov",
            "email": "ivanov@jetstyle.ru"
        },
        {
            "name": "generalov",
            "url": "https://github.com/generalov"
        }
    ],
    "dependencies": {
        "colors": "0.6.0-1",
        "csso": "~1.3.10",
        "express": "2.5.9",
        "glob": "~3.1.14",
        "jade": "0.26.1",
        "lodash-template": "1.0.0",
        "optimist": "~0.3.5",
        "readable-stream": "~1.0.0",
        "source-map": "~0.1.3",
        "uglify-js": "1.3.4"
    },
    "description": "LMD: Lazy Module Declaration",
    "devDependencies": {
        "chai": "*",
        "colors": "~0.6.0",
        "http-server": "~0.5.1",
        "mocha": "1.11.0",
        "phantomjs": "1.9.16",
        "vow": "0.3.12"
    },
    "directories": {},
    "dist": {
        "shasum": "42963efcb842c86294552f45043f1af8f84ab573",
        "tarball": "https://registry.npmjs.org/lmd/-/lmd-1.13.4.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "03410c36839728de683c697670e1b205dc8193ee",
    "homepage": "http://lmdjs.org/",
    "keywords": [
        "lmd",
        "amd",
        "module",
        "components",
        "styles",
        "builder",
        "optimizer",
        "cli",
        "tool"
    ],
    "license": "MIT",
    "main": "./bin/lmd_builder.js",
    "maintainers": [
        {
            "name": "azproduction",
            "email": "azazel.private@gmail.com"
        }
    ],
    "name": "lmd",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/azproduction/lmd.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.13.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module lmd](#apidoc.module.lmd)
1.  [function <span class="apidocSignatureSpan">lmd.</span>Cli.LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter)
1.  [function <span class="apidocSignatureSpan">lmd.</span>Writer (buildResult)](#apidoc.element.lmd.Writer)
1.  [function <span class="apidocSignatureSpan">lmd.</span>super_ ()](#apidoc.element.lmd.super_)
1.  [function <span class="apidocSignatureSpan">lmd.</span>super_.super_ (options)](#apidoc.element.lmd.super_.super_)
1.  [function <span class="apidocSignatureSpan">lmd.</span>watch (configFile, options)](#apidoc.element.lmd.watch)
1.  object <span class="apidocSignatureSpan">lmd.</span>Cli
1.  object <span class="apidocSignatureSpan">lmd.</span>Cli.LogWriter.prototype
1.  object <span class="apidocSignatureSpan">lmd.</span>Writer.prototype
1.  object <span class="apidocSignatureSpan">lmd.</span>coverage_apply
1.  object <span class="apidocSignatureSpan">lmd.</span>lmd_common
1.  object <span class="apidocSignatureSpan">lmd.</span>super_.prototype
1.  object <span class="apidocSignatureSpan">lmd.</span>super_.super_.prototype
1.  object <span class="apidocSignatureSpan">lmd.</span>super_.super_.super_.prototype

#### [module lmd.Cli](#apidoc.module.lmd.Cli)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.</span>LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter)

#### [module lmd.Cli.LogWriter](#apidoc.module.lmd.Cli.LogWriter)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.</span>LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter.LogWriter)

#### [module lmd.Cli.LogWriter.prototype](#apidoc.module.lmd.Cli.LogWriter.prototype)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>error (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.error)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>help (content, errorMessage)](#apidoc.element.lmd.Cli.LogWriter.prototype.help)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>log (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.log)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>ok (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.ok)
1.  [function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>warn (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.warn)

#### [module lmd.Writer](#apidoc.module.lmd.Writer)
1.  [function <span class="apidocSignatureSpan">lmd.</span>Writer (buildResult)](#apidoc.element.lmd.Writer.Writer)

#### [module lmd.Writer.prototype](#apidoc.module.lmd.Writer.prototype)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_isCanWriteStream (stream, fileName)](#apidoc.element.lmd.Writer.prototype._isCanWriteStream)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_logResult (stream, fileName, resourceName)](#apidoc.element.lmd.Writer.prototype._logResult)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_onAllEnd (callback)](#apidoc.element.lmd.Writer.prototype._onAllEnd)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_pipeStreamToFile (stream, fileName)](#apidoc.element.lmd.Writer.prototype._pipeStreamToFile)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_resolvePaths (buildConfig)](#apidoc.element.lmd.Writer.prototype._resolvePaths)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_streamEnd ()](#apidoc.element.lmd.Writer.prototype._streamEnd)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_waitFor (stream, event)](#apidoc.element.lmd.Writer.prototype._waitFor)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_writeStreamsTo (stream, paths, resourceName)](#apidoc.element.lmd.Writer.prototype._writeStreamsTo)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>logTo (cli)](#apidoc.element.lmd.Writer.prototype.logTo)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>relativeTo (cwd)](#apidoc.element.lmd.Writer.prototype.relativeTo)
1.  [function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>writeAll (callback)](#apidoc.element.lmd.Writer.prototype.writeAll)

#### [module lmd.coverage_apply](#apidoc.module.lmd.coverage_apply)
1.  [function <span class="apidocSignatureSpan">lmd.coverage_apply.</span>interpret (moduleName, file, content, lineOffset, options)](#apidoc.element.lmd.coverage_apply.interpret)

#### [module lmd.lmd_common](#apidoc.module.lmd.lmd_common)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>analiseModuleContent (moduleOptions)](#apidoc.element.lmd.lmd_common.analiseModuleContent)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>assembleLmdConfig (configFile, flagsNames, extraOptions, usedConfigs)](#apidoc.element.lmd.lmd_common.assembleLmdConfig)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectFlagsNotifications (config)](#apidoc.element.lmd.lmd_common.collectFlagsNotifications)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectFlagsWarnings (config, deepModulesInfo)](#apidoc.element.lmd.lmd_common.collectFlagsWarnings)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectModules (config, configDir)](#apidoc.element.lmd.lmd_common.collectModules)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectModulesInfo (config)](#apidoc.element.lmd.lmd_common.collectModulesInfo)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>deepDestructableMerge (left, right)](#apidoc.element.lmd.lmd_common.deepDestructableMerge)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>discoverModuleType (moduleName, modulesNames, globalsNames)](#apidoc.element.lmd.lmd_common.discoverModuleType)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getGlobals (config)](#apidoc.element.lmd.lmd_common.getGlobals)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getModuleFileByShortName (lmdDir, shortName)](#apidoc.element.lmd.lmd_common.getModuleFileByShortName)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getSuspiciousNames (config, deepModulesInfo)](#apidoc.element.lmd.lmd_common.getSuspiciousNames)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>groupModulesByBundles (config)](#apidoc.element.lmd.lmd_common.groupModulesByBundles)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>iterateModulesInfo (deepModulesInfo, iterator)](#apidoc.element.lmd.lmd_common.iterateModulesInfo)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>readConfig (file)](#apidoc.element.lmd.lmd_common.readConfig)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>tryExtend (config, configDir)](#apidoc.element.lmd.lmd_common.tryExtend)
1.  [function <span class="apidocSignatureSpan">lmd.lmd_common.</span>wrapModule (code, moduleOptions, moduleType)](#apidoc.element.lmd.lmd_common.wrapModule)
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>GLOBALS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>LMD_GLOBALS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>LMD_PLUGINS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>MASTER_FIELDS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>NODE_GLOBALS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>RE_LMD_FILE
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>SOURCE_TWEAK_FLAGS
1.  object <span class="apidocSignatureSpan">lmd.lmd_common.</span>WORKER_GLOBALS
1.  string <span class="apidocSignatureSpan">lmd.lmd_common.</span>LMD_JS_SRC_PATH
1.  string <span class="apidocSignatureSpan">lmd.lmd_common.</span>ROOT_BUNDLE_ID
1.  string <span class="apidocSignatureSpan">lmd.lmd_common.</span>SUB_BUNDLE_SEPARATOR

#### [module lmd.super_](#apidoc.module.lmd.super_)
1.  [function <span class="apidocSignatureSpan">lmd.</span>super_ (options)](#apidoc.element.lmd.super_.super_)

#### [module lmd.super_.prototype](#apidoc.module.lmd.super_.prototype)
1.  [function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_push ()](#apidoc.element.lmd.super_.prototype._push)
1.  [function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_read (size)](#apidoc.element.lmd.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_write (chunk, encoding, callback)](#apidoc.element.lmd.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>end ()](#apidoc.element.lmd.super_.prototype.end)

#### [module lmd.super_.super_](#apidoc.module.lmd.super_.super_)
1.  [function <span class="apidocSignatureSpan">lmd.super_.</span>super_ (options)](#apidoc.element.lmd.super_.super_.super_)

#### [module lmd.super_.super_.prototype](#apidoc.module.lmd.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype.end)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype.write)

#### [module lmd.super_.super_.super_.prototype](#apidoc.module.lmd.super_.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>_read (n)](#apidoc.element.lmd.super_.super_.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.lmd.super_.super_.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.lmd.super_.super_.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>pause ()](#apidoc.element.lmd.super_.super_.super_.prototype.pause)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.lmd.super_.super_.super_.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.lmd.super_.super_.super_.prototype.push)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>read (n)](#apidoc.element.lmd.super_.super_.super_.prototype.read)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>resume ()](#apidoc.element.lmd.super_.super_.super_.prototype.resume)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.lmd.super_.super_.super_.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.lmd.super_.super_.super_.prototype.unpipe)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.lmd.super_.super_.super_.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.lmd.super_.super_.super_.prototype.wrap)

#### [module lmd.watch](#apidoc.module.lmd.watch)
1.  [function <span class="apidocSignatureSpan">lmd.</span>watch (configFile, options)](#apidoc.element.lmd.watch.watch)



# <a name="apidoc.module.lmd"></a>[module lmd](#apidoc.module.lmd)

#### <a name="apidoc.element.lmd.Cli.LogWriter"></a>[function <span class="apidocSignatureSpan">lmd.</span>Cli.LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter)
- description and source-code
```javascript
Cli.LogWriter = function (stream) {
    this.stream = stream;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer"></a>[function <span class="apidocSignatureSpan">lmd.</span>Writer (buildResult)](#apidoc.element.lmd.Writer)
- description and source-code
```javascript
Writer = function (buildResult) {
    this.source = buildResult;
    this.cwd = process.cwd();
    this.cli = new LogWriter(process.stdout);
    this.pendingStreams = 0;
    this.callback = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_"></a>[function <span class="apidocSignatureSpan">lmd.</span>super_ ()](#apidoc.element.lmd.super_)
- description and source-code
```javascript
function DataStream() {
    Duplex.call(this);
    this._finished = false;
    this._receiverCapacity = 0;
    this._buffer = new Buffer(0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_"></a>[function <span class="apidocSignatureSpan">lmd.</span>super_.super_ (options)](#apidoc.element.lmd.super_.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex))
    return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false)
    this.readable = false;

  if (options && options.writable === false)
    this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false)
    this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.watch"></a>[function <span class="apidocSignatureSpan">lmd.</span>watch (configFile, options)](#apidoc.element.lmd.watch)
- description and source-code
```javascript
watch = function (configFile, options) {
    DataStream.call(this);
    this.options = options || {};
    var self = this;

    this.configFile = configFile;

    this.init();
    this.sourceMap.readable = false;
    this.readable = false;

    // Let return instance before build
    this.watchConfig = this.compileConfig(self.configFile, self.options);

    this.makeEmptyStreamsUnreadable(this.watchConfig);

    var isFatalErrors = !this.isAllModulesExists(this.watchConfig);
    if (isFatalErrors) {
        this.readable = false;
    }
    process.nextTick(function () {
        if (!isFatalErrors) {
            if (!configFile) {
                return;
            }

            if (typeof self.watchConfig.output === 'string') {
                self.fsWatch(self.watchConfig);
                return;
            } else {
                self.log.write('ERRO'.red.inverse + ':' + '    Check your config file. "output" parameter should be a {String} eg
 "../path"'.red + '\n');
                return;
            }
        } else {
            self.printFatalErrors(self.watchConfig);
        }
        self.closeStreams();
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.Cli"></a>[module lmd.Cli](#apidoc.module.lmd.Cli)

#### <a name="apidoc.element.lmd.Cli.LogWriter"></a>[function <span class="apidocSignatureSpan">lmd.Cli.</span>LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter)
- description and source-code
```javascript
LogWriter = function (stream) {
    this.stream = stream;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.Cli.LogWriter"></a>[module lmd.Cli.LogWriter](#apidoc.module.lmd.Cli.LogWriter)

#### <a name="apidoc.element.lmd.Cli.LogWriter.LogWriter"></a>[function <span class="apidocSignatureSpan">lmd.Cli.</span>LogWriter (stream)](#apidoc.element.lmd.Cli.LogWriter.LogWriter)
- description and source-code
```javascript
LogWriter = function (stream) {
    this.stream = stream;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.Cli.LogWriter.prototype"></a>[module lmd.Cli.LogWriter.prototype](#apidoc.module.lmd.Cli.LogWriter.prototype)

#### <a name="apidoc.element.lmd.Cli.LogWriter.prototype.error"></a>[function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>error (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.error)
- description and source-code
```javascript
error = function (message) {
    this.log('ERRO'.red.inverse + ':    ' + message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Cli.LogWriter.prototype.help"></a>[function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>help (content, errorMessage)](#apidoc.element.lmd.Cli.LogWriter.prototype.help)
- description and source-code
```javascript
help = function (content, errorMessage) {
    var help = [
        '',
        'LMD Builder',
        ''
    ];

    help = help.concat(content);

    if (errorMessage) {
        help = help.concat([errorMessage.red, '']);
    }

    help = help.map(function (line) {
        return 'help'.cyan + ':    ' + line;
    }).join('\n');

    this.log(help);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Cli.LogWriter.prototype.log"></a>[function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>log (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.log)
- description and source-code
```javascript
log = function (message) {
    this.stream.write(message + '\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Cli.LogWriter.prototype.ok"></a>[function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>ok (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.ok)
- description and source-code
```javascript
ok = function (message) {
    this.log('info'.green + ':    ' + message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Cli.LogWriter.prototype.warn"></a>[function <span class="apidocSignatureSpan">lmd.Cli.LogWriter.prototype.</span>warn (message)](#apidoc.element.lmd.Cli.LogWriter.prototype.warn)
- description and source-code
```javascript
warn = function (message) {
    this.log('warn'.yellow + ':    ' + message);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.Writer"></a>[module lmd.Writer](#apidoc.module.lmd.Writer)

#### <a name="apidoc.element.lmd.Writer.Writer"></a>[function <span class="apidocSignatureSpan">lmd.</span>Writer (buildResult)](#apidoc.element.lmd.Writer.Writer)
- description and source-code
```javascript
Writer = function (buildResult) {
    this.source = buildResult;
    this.cwd = process.cwd();
    this.cli = new LogWriter(process.stdout);
    this.pendingStreams = 0;
    this.callback = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.Writer.prototype"></a>[module lmd.Writer.prototype](#apidoc.module.lmd.Writer.prototype)

#### <a name="apidoc.element.lmd.Writer.prototype._isCanWriteStream"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_isCanWriteStream (stream, fileName)](#apidoc.element.lmd.Writer.prototype._isCanWriteStream)
- description and source-code
```javascript
_isCanWriteStream = function (stream, fileName) {
    return fileName && stream && stream.readable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._logResult"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_logResult (stream, fileName, resourceName)](#apidoc.element.lmd.Writer.prototype._logResult)
- description and source-code
```javascript
_logResult = function (stream, fileName, resourceName) {
    var cli = this.cli;

    if (this._isCanWriteStream(stream, fileName)) {
        stream.once('end', function () {
            cli.ok('Writing ' + resourceName + ' to ' + fileName.green);
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._onAllEnd"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_onAllEnd (callback)](#apidoc.element.lmd.Writer.prototype._onAllEnd)
- description and source-code
```javascript
_onAllEnd = function (callback) {
    this.callback = callback;

    var self = this,
        bundles = this.source.bundles;

    Object.keys(bundles)
        .map(function (bundleName) {
            return bundles[bundleName];
        })
        .concat([this.source, this.source.log])
        .forEach(function (stream) {
            if (!stream.readable) {
                return;
            }

            self._waitFor(stream, 'end');
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._pipeStreamToFile"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_pipeStreamToFile (stream, fileName)](#apidoc.element.lmd.Writer.prototype._pipeStreamToFile)
- description and source-code
```javascript
_pipeStreamToFile = function (stream, fileName) {
    if (this._isCanWriteStream(stream, fileName)) {
        var writer = fs.createWriteStream(fileName, {
            flags: "w",
            encoding: "utf8",
            mode: 0666
        });

        this._waitFor(writer, 'close');

        stream.pipe(writer);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._resolvePaths"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_resolvePaths (buildConfig)](#apidoc.element.lmd.Writer.prototype._resolvePaths)
- description and source-code
```javascript
_resolvePaths = function (buildConfig) {
    var cwd = this.cwd,
        configs = path.join(cwd, '.lmd'),
        root = path.resolve(configs, buildConfig.root || ''),
        sourceMap = buildConfig.sourcemap ? path.resolve(root, buildConfig.sourcemap) : null,
        source = buildConfig.output ? path.resolve(root, buildConfig.output) : null,
        style = buildConfig.styles_output ? path.resolve(root, buildConfig.styles_output) : null;

    return {
        configs: configs,
        root: root,
        sourceMap: sourceMap,
        source: source,
        style: style
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._streamEnd"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_streamEnd ()](#apidoc.element.lmd.Writer.prototype._streamEnd)
- description and source-code
```javascript
_streamEnd = function () {
    var self = this;

    this.pendingStreams--;
    if (this.callback && this.pendingStreams <= 0) {
        // setImmediate
        setTimeout(function () {
            self.callback();
        }, 0);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._waitFor"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_waitFor (stream, event)](#apidoc.element.lmd.Writer.prototype._waitFor)
- description and source-code
```javascript
_waitFor = function (stream, event) {
    var self = this;

    if (!stream) {
        return;
    }

    this.pendingStreams++;
    stream.once(event, function () {
        self._streamEnd();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype._writeStreamsTo"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>_writeStreamsTo (stream, paths, resourceName)](#apidoc.element.lmd.Writer.prototype._writeStreamsTo)
- description and source-code
```javascript
_writeStreamsTo = function (stream, paths, resourceName) {
    this._logResult(stream, paths.source, 'LMD ' + resourceName);
    this._pipeStreamToFile(stream, paths.source);

    this._logResult(stream.sourceMap, paths.sourceMap, 'Source Map of ' + resourceName);
    this._pipeStreamToFile(stream.sourceMap, paths.sourceMap);

    this._logResult(stream.style, paths.style, 'Style of ' + resourceName);
    this._pipeStreamToFile(stream.style, paths.style);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype.logTo"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>logTo (cli)](#apidoc.element.lmd.Writer.prototype.logTo)
- description and source-code
```javascript
logTo = function (cli) {
    if (!(cli instanceof LogWriter)) {
        throw new TypeError('cli should be instance of LogWriter');
    }

    this.cli = cli;

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype.relativeTo"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>relativeTo (cwd)](#apidoc.element.lmd.Writer.prototype.relativeTo)
- description and source-code
```javascript
relativeTo = function (cwd) {
    this.cwd = cwd;

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.Writer.prototype.writeAll"></a>[function <span class="apidocSignatureSpan">lmd.Writer.prototype.</span>writeAll (callback)](#apidoc.element.lmd.Writer.prototype.writeAll)
- description and source-code
```javascript
writeAll = function (callback) {
    var cli = this.cli,
        self = this,
        source = this.source,

        buildConfig = this.source.buildConfig,
        configFile = this.source.configFile,
        buildName = path.basename(configFile).split('.lmd')[0],

        paths = this._resolvePaths(buildConfig),

        isPrintToStdout = paths.source === null,
        isCanLog = buildConfig.log && !isPrintToStdout;

    // fatal error
    if (source.readable === false && isCanLog) {
        source.log.pipe(cli.stream);
        callback('fatal');
        return;
    }

    if (isPrintToStdout) {
        source.pipe(cli.stream);
        callback(null);
        return;
    }

    this._onAllEnd(callback);

    if (isCanLog) {
        var versionString = buildConfig.version ? ' - version ' + buildConfig.version.toString().cyan : '';
        cli.ok('Building '' + buildName.green +  '' (' + ('.lmd/' + buildName + '.lmd.js(on)').green + ')' + versionString);
        if (buildConfig.mixins && buildConfig.mixins.length) {
            cli.ok('Extra mixins ' + buildConfig.mixins.map(function (mixinName) {
                return mixinName.green
            }).join(', '));
        }
    }

    // Print package
    this._writeStreamsTo(source, paths, 'Package');

    // Print bundles
    var bundles = buildConfig.bundles;
    Object.keys(bundles).forEach(function (bundleName) {
        var stream = source.bundles[bundleName],
            paths = self._resolvePaths(bundles[bundleName]);

        self._writeStreamsTo(stream, paths, 'Bundle ' + bundleName.green);
    });

    // Print warnings log
    if (isCanLog) {
        source.log.pipe(cli.stream);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.coverage_apply"></a>[module lmd.coverage_apply](#apidoc.module.lmd.coverage_apply)

#### <a name="apidoc.element.lmd.coverage_apply.interpret"></a>[function <span class="apidocSignatureSpan">lmd.coverage_apply.</span>interpret (moduleName, file, content, lineOffset, options)](#apidoc.element.lmd.coverage_apply.interpret)
- description and source-code
```javascript
interpret = function (moduleName, file, content, lineOffset, options) {
	options = options || {
		"function" : true,
		"condition" : true
	};

	try {
		var tree = parser.parse(content, false, true);
	} catch (e) {
		return {
            error: "Error instrumentig file " + file + " " + e.message
        }
	}

	var walker = uglify.ast_walker();
	// this is the list of nodes being analyzed by the walker
	// without this, w.walk(this) would re-enter the newly generated code with infinite recursion
	var analyzing = [];
	// list of all lines' id encounterd in this file
	var lines = [];
	// list of all conditions' id encounterd in this file
	var allConditions = [];
	// list of all functions' id encounterd in this file
	var allFunctions = [];
	// anonymous function takes the name of their var definition
	var candidateFunctionName = null;

    var isFirstFunction = true,
        isFirstLine = true;

	<span class="apidocCodeCommentSpan">/**
	 * A statement was found in the file, remember its id.
	 */
</span>	function rememberStatement (id) {
		lines.push(id);
	};

	/**
	 * A function was found in the file, remember its id.
	 */
	function rememberFunction (id) {
		allFunctions.push(id);
	};

	/**
	 * Generic function for counting a line.
	 * It generates a lineId from the line number and the block name (in minified files there
	 * are more logical lines on the same file line) and adds a function call before the actual
	 * line of code.
	 *
	 * 'this' is any node in the AST
	 */
	function countLine() {
		var ret;
        // skip first line
        if (isFirstLine) {
            isFirstLine = false;
            return ret;
        }
		if (this[0].start && analyzing.indexOf(this) < 0) {
			giveNameToAnonymousFunction.call(this);
			var lineId = this[0].start.line + lineOffset + ''; //this[0].name + ':' + this[0].start.line + ":" + this[0].start.pos;
			rememberStatement(lineId);

			analyzing.push(this);
			ret = [ "splice",
				[
					[ "stat",
						[ "call",
                            ["dot", ["name", "require"], "coverage_line"],
							[
								[ "string", moduleName],
								[ "string", lineId]
							]
						]
					],
					walker.walk(this)
				]
			];
			analyzing.pop(this);
		}
		return ret;
	};

	/**
	 * Walker for 'if' nodes. It overrides countLine because we want to instrument conditions.
	 *
	 * 'this' is an if node, so
	 *    'this[0]' is the node descriptor
	 *    'this[1]' is the decision block
	 *    'this[2]' is the 'then' code block
	 *    'this[3]' is the 'else' code block
	 *
	 * Note that if/else if/else in AST are represented as nested if/else
	 */
	function countIf() {
		var self = this, ret;
		if (self[0].start && analyzing.indexOf(self) < 0) {
			var decision = self[1];
			var lineId = self[0].name + ':' + (self[0].start.line + lineOffset);

			self[1] = wrapCondition(decision, lineId);

			// We are adding new lines, make sure code blocks are actual blocks
			if (self[2] && self[2][0].start && self[2][0].start.value != "{") {
				self[2] = [ "block", [self[2]]];
			}

			if (self[3] && self[3][0].start && self[3][0].start.value != "{") {
				self[3] = [ "block", [self[3]]];
			}
		}

		ret = countLine.call(self);

		if (decision) {
			analyzing.pop(decision);
		}

		return ret;
	};

	/**
	 * This is the key function for condition coverage as it wraps every condition in
	 * a function call.
	 * The condition id is generated fron the lineId (@see countLine) plus the character
	 * position of the condition.
	 */
	function wrapCondition(decision, lineId, parentPos) {
		if (options.condition === false) {
			// condition coverage is disabled
			return decision;
		}

		if (isSingleCondition(decision)) {
			var pos = getPositionStart(decision, parentPos);
			var condId = lineId + ":" + pos;

			analyzing.push(decision);
			allConditions.push(condId);
			return ["call",
                ["dot", ["name", "require"], "coverage_condition"],
				[
					[ "string", moduleName ],
					[ "string", condId],
					decision
				]
			];
		} else {
			decision[2] = wrapCondition(decision[2], lineId, getPositionStart(decision, parentPos));
			decision[3] = wrapCondition(decision[3], ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.lmd_common"></a>[module lmd.lmd_common](#apidoc.module.lmd.lmd_common)

#### <a name="apidoc.element.lmd.lmd_common.analiseModuleContent"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>analiseModuleContent (moduleOptions)](#apidoc.element.lmd.lmd_common.analiseModuleContent)
- description and source-code
```javascript
analiseModuleContent = function (moduleOptions) {
    var moduleDescriptor = {
            type: "",
            warns: [],
            code: null,
            originalCode: null,
            depends: [],
            features: {}
        };

    if (moduleOptions.is_shortcut) {
        moduleDescriptor.type = "shortcut";
        moduleDescriptor.features.shortcuts = true;

        return moduleDescriptor;
    }

    if (!moduleOptions.is_exists) {
        moduleDescriptor.type = "not-exists";

        return moduleDescriptor;
    }

    var modulePath = [].concat(moduleOptions.path);

    var code = modulePath.map(function (modulePath) {
        return fs.readFileSync(modulePath, 'utf8');
    }).join('\n/* joined by builder */\n');

    var ast;

    moduleDescriptor.code = code;
    moduleDescriptor.originalCode = code;

    try {
        JSON.parse(code);
        moduleDescriptor.type = "json";
        return moduleDescriptor;
    } catch (e) {}

    try {
        ast = parser.parse(code);
    } catch (e) {
        moduleDescriptor.type = "string";

        var isOneOfModulesIsJs = modulePath.some(function (modulePath) {
            return /.js$/.test(modulePath);
        });

        if (isOneOfModulesIsJs) {
            moduleDescriptor.type = "string";
            moduleDescriptor.warns
                .push('File "**' + modulePath.join('**", "**') + '**" has extension **.js** and LMD detect an parse error. \n' +
                    e.toString().red +
                    '\nThis module will be string. Please check the source.');
        }
        return moduleDescriptor;
    }

    if (moduleOptions.is_third_party) {
        moduleDescriptor.type = "3-party";
    } else {
        moduleDescriptor.type = getModuleType(ast);
    }

    // Apply type type hint
    if (moduleOptions.type_hint) {
        // Unexpected module type
        if (!MODULE_TYPE_HINTS.hasOwnProperty(moduleOptions.type_hint)) {
            moduleDescriptor.warns
                .push('Unexpected module type hint '' + moduleOptions.type_hint + '' of module "' + String(moduleOptions.name).green
 + '". ' +
                    'Only these types are supported: ' + Object.keys(MODULE_TYPE_HINTS).join(', '));
        } else {
            // Good type hint
            moduleDescriptor.type = moduleOptions.type_hint;
        }
    }

    moduleDescriptor.code = wrapModule(moduleDescriptor.code, moduleOptions, moduleDescriptor.type);

    if (moduleDescriptor.type === '3-party') {
        var extraRequires = []
            .concat(collect3partyDepends(moduleOptions.extra_bind))
            .concat(collect3partyDepends(moduleOptions.extra_require));

        if (extraRequires.length && moduleOptions.is_sandbox) {
            moduleDescriptor.warns
                .push('Your module "**' + modulePath.join('**", "**') + '**" have to require() some dependencies, but it is sandboxed
. ' +
                'Remove sandbox flag to allow module require().');
        }

        Array.prototype.push.apply(moduleDescriptor.depends, extraRequires);
    }

    var requireExpressions = findRequireAccesses(ast, moduleDescriptor.type),
        analyticsResult = findModuleRequirementsAndFeatures(requireExpressions);

    moduleDescriptor.features = analyticsResult.features;
    moduleDescriptor.depends = moduleDescriptor.depends.concat(analyticsResult.depends);

    moduleDescriptor.depends = moduleDescriptor.depends.filter(function(item, index, array) {
        return array.indexOf(item, index + 1) < 0;
    });

    if (moduleDescriptor.type === "amd") {
        moduleDescriptor.features.amd = true;
        moduleDescriptor.depends = addExtraAmdDepends(ast, moduleDescriptor.depends);
    }

    return moduleDescriptor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.assembleLmdConfig"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>assembleLmdConfig (configFile, flagsNames, extraOptions, usedConfigs)](#apidoc.element.lmd.lmd_common.assembleLmdConfig)
- description and source-code
```javascript
assembleLmdConfig = function (configFile, flagsNames, extraOptions, usedConfigs) {
    var configDir = path.dirname(configFile),
        rawConfig = readConfig(configFile);

    configFile = fs.realpathSync(configFile);
    return assembleLmdConfigAsObject(rawConfig, configFile, configDir, flagsNames, extraOptions, usedConfigs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.collectFlagsNotifications"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectFlagsNotifications (config)](#apidoc.element.lmd.lmd_common.collectFlagsNotifications)
- description and source-code
```javascript
collectFlagsNotifications = function (config) {
    var result = [], dependsOf;
    if (config.plugins_depends) {
        for (var dependsName in config.plugins_depends) {
            dependsOf = config.plugins_depends[dependsName];

            result.push('Extra plugin was added ' + ('"' + dependsName + '"').green + ': ' + 'true'.green + '. This is depends of
 ' + dependsOf.join(', ').cyan + '.');
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.collectFlagsWarnings"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectFlagsWarnings (config, deepModulesInfo)](#apidoc.element.lmd.lmd_common.collectFlagsWarnings)
- description and source-code
```javascript
collectFlagsWarnings = function (config, deepModulesInfo) {
    var featureWarnings = {},
        result = [],
        is_using_shortcuts = false,
        is_using_amd = false;

    // aggregate usage
    iterateModulesInfo(deepModulesInfo, function (module, moduleName, bundleName) {
        if (module.type === "amd") {
            is_using_amd = true;
        }
        if (module.type === "shortcut") {
            is_using_shortcuts = true;
        }
        var features = module.features;
        for (var featureName in features) {
            if (typeof config[featureName] === "undefined" || config[featureName] === false) {
                if (!featureWarnings[featureName]) {
                    featureWarnings[featureName] = [];
                }
                if (bundleName === ROOT_BUNDLE_ID) {
                    featureWarnings[featureName].push(moduleName);
                } else {
                    featureWarnings[featureName].push(bundleName + SUB_BUNDLE_SEPARATOR + moduleName);
                }
            }
        }
    });

    for (var featureName in featureWarnings) {
        result.push("Required " + ("\"" + featureName + "\"").green + ": " + "true".green +
                    ". Some of your modules (" + (featureWarnings[featureName].join(', ')).cyan + ") are uses feature " + ("'" +
featureName + "'").green + ", " +
                    "but it disable in this build.");
    }

    if (!is_using_shortcuts && config.shortcuts) {
        result.push('Config flag ' + ''shortcuts''.green + ' is enabled, but there is no shortcuts in your package. ' +
                  'Disable that flag to optimize your package.');
    }

    if (!is_using_amd && config.amd) {
        result.push('Config flag ' + ''amd''.green + ' is enabled, but there is no AMD Modules in your package. ' +
                  'Disable that flag to optimize your package.');
    }

    if (config.stats_coverage && (config.cache || config.cache_async)) {
        result.push('LMD will cache your modules under code coverage. You can disable ' + ''cache''.green + ' and ' + ''cache_async
''.green + ' flags.');
    }

    if (config.async_plain && config.async_plainonly) {
        result.push('You are using both config flags ' + ''async_plain''.green + ' and ' + ''async_plainonly''.green + '. Disable
 one to optimise your source.');
    }

    if (!config.stats_coverage && config.stats_coverage_async) {
        result.push('You are using ' + ''stats_coverage_async''.green + ' without ' + ''stats_coverage''.green + '. Enable ' + ''
stats_coverage''.green + ' flag.');
    }

    if (!config.async && config.stats_coverage_async) {
        result.push('You are using ' + ''stats_coverage_async''.green + ' but not using ' + ''async''.green + '. Disable ' + ''stats_coverage_async
''.green + ' flag.');
    }

    if ('promise' in config && typeof config.promise !== "string") {
        result.push(''promise''.green + ' should be a string pointing to the deferred factory function. eg ' + '"promise"'.green
 + ': ' + '"$.Deferred"'.green);
    }

    if ('banner' in config) {
        if (typeof config.banner !== 'string') {
            result.push(''banner''.green + ' should be a string');
        } else {
            // Banner should not contain any javascript. Checking it.
            try {
                var ast = parser.parse(config.banner);
                if (ast[1].length !== 0) {
                    result.push(''banner''.green + ' should be a JavaScript comment. Please remove any executable JavaScript from
 ' + ''banner''.green + '.');
                }
            } catch (e) {
                result.push('Something is wrong with your ' + ''banner''.green + ', please check it');
            }
        }
    }

    var warnings = {
        globals: 'Some of your modules are undeclared (register them as ' + '"name"'.green + ': ' + '"@shortcut"'.green + ' or use
 directly if they are globals):',
        modules: 'Some of our modules are probably off-package (you can register them as ' + '"name"'.green + ': ' + '"@shortcut
"'.green + '):',
        unused: 'Some of your modu ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.collectModules"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectModules (config, configDir)](#apidoc.element.lmd.lmd_common.collectModules)
- description and source-code
```javascript
collectModules = function (config, configDir) {
    var modules = {},
        globalLazy = config.lazy || false,
        globalDepends = (config.depends === true ? DEFAULT_DEPENDS_MASK : config.depends) || false,
        moduleLazy = false,
        moduleTypeHint,
        moduleName,
        modulePath,
        moduleRealPath,
        moduleExists,
        moduleExports,
        moduleRequire,
        moduleBind,
        moduleFileName,
        moduleFilePath,
        moduleDesciptor,
        wildcardRegex,
        isMultiPathModule,
        moduleData,
        isThirdPartyModule,
        modulesDirPath = config.root || config.path || '';

    modulesDirPath = path.resolve(configDir, modulesDirPath);

    // grep paths
    for (moduleName in config.modules) {
        moduleDesciptor = config.modules[moduleName];
        // case "moduleName": null
        // case "moduleName": "path/to/module.js"
        if (moduleDesciptor === null || typeof moduleDesciptor === "string" || Array.isArray(moduleDesciptor)) {
            moduleTypeHint = false;
            moduleExports = false;
            moduleRequire = false;
            moduleBind = false;
            modulePath = moduleDesciptor;
            moduleLazy = globalLazy;
        } else { // case "moduleName": {"path": "path/to/module.js", "lazy": false}
            moduleTypeHint = moduleDesciptor.type || false;
            moduleExports = moduleDesciptor.exports || false;
            moduleRequire = moduleDesciptor.require || false;
            moduleBind = moduleDesciptor.bind || moduleDesciptor['this'] || false;
            modulePath = moduleDesciptor.path;
            moduleLazy = moduleDesciptor.lazy || false;
            moduleTypeHint = moduleDesciptor.type || false;
        }

        isMultiPathModule = false;
        if (Array.isArray(modulePath)) {
            // Try to glob
            // case when ['jquery*.js']
            modulePath = modulePath.reduce(function (paths, modulePath) {
                if (globPattern.test(modulePath)) {
                    modulePath = glob.sync(modulePath, {
                        cwd: modulesDirPath,
                        nosort: true
                    }) || [];
                }

                return paths.concat(modulePath);
            }, []);

            // case when ['jquery.js']
            if (modulePath.length === 1) {
                modulePath = modulePath[0];
            } else {
                isMultiPathModule = true;
            }
        }

        isThirdPartyModule = !!moduleExports || !!moduleRequire || !!moduleBind;

        // Override if cache flag = true
        if (config.cache) {
            moduleLazy = true;
        }

        // its a glob pattern
        // @see https://github.com/isaacs/node-glob
        if (!isMultiPathModule && globPattern.test(modulePath)) {
            var globModules = glob.sync(modulePath, {
                cwd: modulesDirPath,
                nosort: true
            });

            // * -> <%= file => for backward capability
            var moduleNameTemplate = template(moduleName.replace('*', '<%= file %>'));

            globModules.forEach(function (module) {
                var moduleRealPath = path.join(modulesDirPath, module),
                    basename = path.basename(moduleRealPath),
                    fileParts = basename.split('.'),
                    ext = fileParts.pop(),
                    file = fileParts.join('.'),
                    dir = path.dirname(moduleRealPath).split(path.sep).reverse(),
                    subdir = createSubdirTemplateVariable(modulesDirPath, moduleRealPath);

                // modify module name using template
                var newModuleName = moduleNameTemplate({
                    basename: basename,
                    file: file,
                    ext: ext,
                    dir: dir,
                    subdir: subdir
                });

                moduleExists = true;
                try {
                    moduleRealPath = fs.realpathSync(moduleRealPath);
                } catch (e) {
                    modul ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.collectModulesInfo"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>collectModulesInfo (config)](#apidoc.element.lmd.lmd_common.collectModulesInfo)
- description and source-code
```javascript
collectModulesInfo = function (config) {
    var result = {};

    var bundles = groupModulesByBundles(config);
    iterateModulesInfo(bundles, function (moduleOptions, moduleName, bundleName) {
        if (!result[bundleName]) {
            result[bundleName] = {};
        }
        result[bundleName][moduleName] = analiseModuleContent(moduleOptions);
    });

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.deepDestructableMerge"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>deepDestructableMerge (left, right)](#apidoc.element.lmd.lmd_common.deepDestructableMerge)
- description and source-code
```javascript
deepDestructableMerge = function (left, right) {
    for (var prop in right) {
        if (right.hasOwnProperty(prop))  {
            if (typeof left[prop] === "object") {
                deepDestructableMerge(left[prop], right[prop]);
            } else {
                left[prop] = right[prop];
            }
        }
    }
    return left;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.discoverModuleType"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>discoverModuleType (moduleName, modulesNames, globalsNames)](#apidoc.element.lmd.lmd_common.discoverModuleType)
- description and source-code
```javascript
function discoverModuleType(moduleName, modulesNames, globalsNames) {
    if (moduleName instanceof RegExp) {
        return 'regexp';
    }

    if (modulesNames.indexOf(moduleName) != -1) {
        return 'in-package';
    }

    if (typeof globalsNames[moduleName] !== "undefined") {
        return 'global';
    }

    if (/\.[a-z]{1,}$/.test(moduleName)) {
        return 'off-package?';
    }

    return 'global?';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.getGlobals"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getGlobals (config)](#apidoc.element.lmd.lmd_common.getGlobals)
- description and source-code
```javascript
function getGlobals(config) {
    var result = {},
        names = ['GLOBALS'];

    if (config.node) {
        names.push('NODE_GLOBALS');
    }

    if (config.worker) {
        names.push('WORKER_GLOBALS');
    }

    names.forEach(function (name) {
        var globalNames = exports[name];
        for (var name in globalNames) {
            result[name] = globalNames[name];
        }
    });

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.getModuleFileByShortName"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getModuleFileByShortName (lmdDir, shortName)](#apidoc.element.lmd.lmd_common.getModuleFileByShortName)
- description and source-code
```javascript
function getModuleFileByShortName(lmdDir, shortName) {
    var files;

    try {
        files = fs.readdirSync(lmdDir);
    } catch (e) {
        return void 0;
    }

    for (var i = 0, c = files.length, fileName; i < c; i++) {
        fileName = files[i];
        var fileExtension = (fileName.match(reLmdFile) || 0)[0];
        if (fileExtension && path.basename(fileName, fileExtension) === shortName) {
            return fileName;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.getSuspiciousNames"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>getSuspiciousNames (config, deepModulesInfo)](#apidoc.element.lmd.lmd_common.getSuspiciousNames)
- description and source-code
```javascript
function getSuspiciousNames(config, deepModulesInfo) {
    var globalsNames = getGlobals(config),
        suspiciousNames = {
            globals: [],
            modules: [],
            unused: [],
            conflicts: {}
        },
        suspiciousNamesIndex = {
            globals: {},
            modules: {},
            unused: {}
        };

    // list of RegExp that require.match() is using
    var matchRegExpList = [];

    var bundles = groupModulesByBundles(config);

    // all module names
    var modulesNames = [];
    iterateModulesInfo(bundles, function (module, name, bundleName) {
        modulesNames.push(name);
    });

    function isMainModuleOf(name, bundleName) {
        if (bundleName === ROOT_BUNDLE_ID) {
            return config.main === name;
        }
        if (config.bundles[bundleName]) {
            return config.bundles[bundleName].main === name;
        }
        return false;
    }

    iterateModulesInfo(bundles, function (module, name, bundleName) {
        if (!suspiciousNamesIndex.unused.hasOwnProperty(name)) {
            suspiciousNamesIndex.unused[name] = false;
        }

        // count names across bundles
        if (!suspiciousNames.conflicts[name]) {
            suspiciousNames.conflicts[name] = [];
        }
        // do not count main modules they can't conflict
        if (!isMainModuleOf(name, bundleName)) {
            suspiciousNames.conflicts[name].push(bundleName);
        }

        var depends = deepModulesInfo[bundleName][name].depends;
        depends.forEach(function (name) {
            var moduleType = discoverModuleType(name, modulesNames, globalsNames);

            // Add this regexp list to use later
            if (moduleType === 'regexp') {
                matchRegExpList.push(name);
                return;
            }

            // skip special LMD names
            if (typeof exports.LMD_GLOBALS[name] !== "undefined") {
                return;
            }

            if (moduleType === 'global?' && !suspiciousNamesIndex.globals[name]) {
                suspiciousNamesIndex.globals[name] = true;
                suspiciousNames.globals.push(name);
            }

            if (moduleType === 'off-package?' && !suspiciousNamesIndex.modules[name]) {
                suspiciousNamesIndex.modules[name] = true;
                suspiciousNames.modules.push(name);
            }

            suspiciousNamesIndex.unused[name] = true;
        });
    });

    // add unused
    iterateModulesInfo(bundles, function (module, name, bundleName) {
        if (config.main === name) {
            return;
        }
        if (!suspiciousNamesIndex.unused[name]) {
            // If one of module.match() regex matches name - module is used
            // do not add it to unused list
            var isMatch = matchRegExpList.some(function (regexp) {
                return regexp.test(name);
            });

            if (!isMatch) {
                suspiciousNames.unused.push(name);
            }
        }
    });

    // Cleanup module names without conflicts across bundles
    var conflicts = suspiciousNames.conflicts;
    suspiciousNames.conflicts = Object.keys(conflicts).reduce(function (result, moduleName) {
        if (conflicts[moduleName].length > 1) {
            result[moduleName] = conflicts[moduleName];
        }

        return result;
    }, {});

    return suspiciousNames;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.groupModulesByBundles"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>groupModulesByBundles (config)](#apidoc.element.lmd.lmd_common.groupModulesByBundles)
- description and source-code
```javascript
groupModulesByBundles = function (config) {
    var bundles = {};

    bundles[ROOT_BUNDLE_ID] = config.modules || {};
    Object.keys(config.bundles || {}).forEach(function (bundleName) {
        bundles[bundleName] = config.bundles[bundleName].modules;
    });

    return bundles;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.iterateModulesInfo"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>iterateModulesInfo (deepModulesInfo, iterator)](#apidoc.element.lmd.lmd_common.iterateModulesInfo)
- description and source-code
```javascript
iterateModulesInfo = function (deepModulesInfo, iterator) {
    Object.keys(deepModulesInfo).forEach(function (bundleName) {
        var modules = deepModulesInfo[bundleName];
        if (!modules) {
            return;
        }
        Object.keys(modules).forEach(function (moduleName) {
            iterator(modules[moduleName], moduleName, bundleName);
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.readConfig"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>readConfig (file)](#apidoc.element.lmd.lmd_common.readConfig)
- description and source-code
```javascript
readConfig = function (file) {
    file = path.join.apply(path, arguments);

    var fileContent = fs.readFileSync(file, 'utf8'),
        config;

    if (path.extname(file) === '.json') {
        // require() is Caches json files
        config = JSON.parse(fileContent);
    } else {
        var mod = new Module('.', null);
        mod.load(file);
        config = mod.exports;
    }

    // Some extra variables
    var data = {
        __dirname: path.dirname(file),
        __filename: file
    };
    for (var key in config) {
        data[key] = config[key];
    }

    return interpolateConfigStrings(config, data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.tryExtend"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>tryExtend (config, configDir)](#apidoc.element.lmd.lmd_common.tryExtend)
- description and source-code
```javascript
tryExtend = function (config, configDir) {
    config = config || {};
    if (typeof config.extends !== "string") {
        return config;
    }

    var parentConfig = tryExtend(readConfig(configDir, config.extends), configDir);

    return deepDestructableMerge(parentConfig, config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.lmd_common.wrapModule"></a>[function <span class="apidocSignatureSpan">lmd.lmd_common.</span>wrapModule (code, moduleOptions, moduleType)](#apidoc.element.lmd.lmd_common.wrapModule)
- description and source-code
```javascript
wrapModule = function (code, moduleOptions, moduleType) {
    switch (moduleType) {
        case "3-party":
            // create lmd module from non-lmd module
            code = wrap3partyModule(code, moduleOptions);
            break;

        case "plain":
            // wrap plain module
            code = wrapPlainModule(code);
            break;

        case "amd":
            // AMD RequireJS
            code = wrapAmdModule(code);
            break;

        case "fd":
        case "fe":
            // wipe tail ;
            code = removeTailSemicolons(code);
    }

    return code;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.super_"></a>[module lmd.super_](#apidoc.module.lmd.super_)

#### <a name="apidoc.element.lmd.super_.super_"></a>[function <span class="apidocSignatureSpan">lmd.</span>super_ (options)](#apidoc.element.lmd.super_.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex))
    return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false)
    this.readable = false;

  if (options && options.writable === false)
    this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false)
    this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.super_.prototype"></a>[module lmd.super_.prototype](#apidoc.module.lmd.super_.prototype)

#### <a name="apidoc.element.lmd.super_.prototype._push"></a>[function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_push ()](#apidoc.element.lmd.super_.prototype._push)
- description and source-code
```javascript
_push = function () {
    // ALL written & flushed
    if (this._finished && this._buffer.length === 0) {
        this.push(null);
        return;
    }

    // Nothing to read or ca not write
    if (!this._receiverCapacity || !this._buffer.length) {
        return;
    }

    var chunkSize = this._receiverCapacity > this._buffer.length ? this._buffer.length : this._receiverCapacity;
    var chunk = this._buffer.slice(0, chunkSize);
    this._receiverCapacity -= chunk.length;

    this._buffer = this._buffer.slice(chunk.length);
    this.push(chunk);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_read (size)](#apidoc.element.lmd.super_.prototype._read)
- description and source-code
```javascript
_read = function (size) {
    this._receiverCapacity += size;
    this._push();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>_write (chunk, encoding, callback)](#apidoc.element.lmd.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, callback) {
    this._buffer = Buffer.concat([this._buffer, new Buffer(chunk, encoding)]);
    this._push();
    callback();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.prototype.end"></a>[function <span class="apidocSignatureSpan">lmd.super_.prototype.</span>end ()](#apidoc.element.lmd.super_.prototype.end)
- description and source-code
```javascript
end = function () {
    Duplex.prototype.end.apply(this, arguments);
    this._finished = true;
    this._push();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.super_.super_"></a>[module lmd.super_.super_](#apidoc.module.lmd.super_.super_)

#### <a name="apidoc.element.lmd.super_.super_.super_"></a>[function <span class="apidocSignatureSpan">lmd.super_.</span>super_ (options)](#apidoc.element.lmd.super_.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.super_.super_.prototype"></a>[module lmd.super_.super_.prototype](#apidoc.module.lmd.super_.super_.prototype)

#### <a name="apidoc.element.lmd.super_.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('not implemented'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.prototype.end"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (typeof chunk === 'function') {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (typeof chunk !== 'undefined' && chunk !== null)
    this.write(chunk, encoding);

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished)
    endWritable(this, state, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.prototype.write"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.lmd.super_.super_.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;

  if (typeof encoding === 'function') {
    cb = encoding;
    encoding = null;
  }

  if (Buffer.isBuffer(chunk))
    encoding = 'buffer';
  else if (!encoding)
    encoding = state.defaultEncoding;

  if (typeof cb !== 'function')
    cb = function() {};

  if (state.ended)
    writeAfterEnd(this, state, cb);
  else if (validChunk(this, state, chunk, cb))
    ret = writeOrBuffer(this, state, chunk, encoding, cb);

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.super_.super_.super_.prototype"></a>[module lmd.super_.super_.super_.prototype](#apidoc.module.lmd.super_.super_.super_.prototype)

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>_read (n)](#apidoc.element.lmd.super_.super_.super_.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  this.emit('error', new Error('not implemented'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.lmd.super_.super_.super_.prototype.addListener)
- description and source-code
```javascript
addListener = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data' && !this._readableState.flowing)
    emitDataEvents(this);

  if (ev === 'readable' && this.readable) {
    var state = this._readableState;
    if (!state.readableListening) {
      state.readableListening = true;
      state.emittedReadable = false;
      state.needReadable = true;
      if (!state.reading) {
        this.read(0);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.lmd.super_.super_.super_.prototype.on)
- description and source-code
```javascript
on = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  if (ev === 'data' && !this._readableState.flowing)
    emitDataEvents(this);

  if (ev === 'readable' && this.readable) {
    var state = this._readableState;
    if (!state.readableListening) {
      state.readableListening = true;
      state.emittedReadable = false;
      state.needReadable = true;
      if (!state.reading) {
        this.read(0);
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.pause"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>pause ()](#apidoc.element.lmd.super_.super_.super_.prototype.pause)
- description and source-code
```javascript
pause = function () {
  emitDataEvents(this, true);
  this.emit('pause');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.pipe"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.lmd.super_.super_.super_.prototype.pipe)
- description and source-code
```javascript
pipe = function (dest, pipeOpts) {
  var src = this;
  var state = this._readableState;

  switch (state.pipesCount) {
    case 0:
      state.pipes = dest;
      break;
    case 1:
      state.pipes = [state.pipes, dest];
      break;
    default:
      state.pipes.push(dest);
      break;
  }
  state.pipesCount += 1;

  var doEnd = (!pipeOpts || pipeOpts.end !== false) &&
              dest !== process.stdout &&
              dest !== process.stderr;

  var endFn = doEnd ? onend : cleanup;
  if (state.endEmitted)
    process.nextTick(endFn);
  else
    src.once('end', endFn);

  dest.on('unpipe', onunpipe);
  function onunpipe(readable) {
    if (readable !== src) return;
    cleanup();
  }

  function onend() {
    dest.end();
  }

  // when the dest drains, it reduces the awaitDrain counter
  // on the source.  This would be more elegant with a .once()
  // handler in flow(), but adding and removing repeatedly is
  // too slow.
  var ondrain = pipeOnDrain(src);
  dest.on('drain', ondrain);

  function cleanup() {
    // cleanup event handlers once the pipe is broken
    dest.removeListener('close', onclose);
    dest.removeListener('finish', onfinish);
    dest.removeListener('drain', ondrain);
    dest.removeListener('error', onerror);
    dest.removeListener('unpipe', onunpipe);
    src.removeListener('end', onend);
    src.removeListener('end', cleanup);

    // if the reader is waiting for a drain event from this
    // specific writer, then it would cause it to never start
    // flowing again.
    // So, if this is awaiting a drain, then we just call it now.
    // If we don't know, then assume that we are waiting for one.
    if (!dest._writableState || dest._writableState.needDrain)
      ondrain();
  }

  // if the dest has an error, then stop piping into it.
  // however, don't suppress the throwing behavior for this.
  function onerror(er) {
    unpipe();
    dest.removeListener('error', onerror);
    if (EE.listenerCount(dest, 'error') === 0)
      dest.emit('error', er);
  }
  // This is a brutally ugly hack to make sure that our error handler
  // is attached before any userland ones.  NEVER DO THIS.
  if (!dest._events || !dest._events.error)
    dest.on('error', onerror);
  else if (isArray(dest._events.error))
    dest._events.error.unshift(onerror);
  else
    dest._events.error = [onerror, dest._events.error];



  // Both close and finish should trigger unpipe, but only once.
  function onclose() {
    dest.removeListener('finish', onfinish);
    unpipe();
  }
  dest.once('close', onclose);
  function onfinish() {
    dest.removeListener('close', onclose);
    unpipe();
  }
  dest.once('finish', onfinish);

  function unpipe() {
    src.unpipe(dest);
  }

  // tell the dest that it's being piped to
  dest.emit('pipe', src);

  // start the flow if it hasn't been started already.
  if (!state.flowing) {
    // the handler that waits for readable events after all
    // the data gets sucked out in flow.
    // This would be easier to follow with a .once() handler
    // in flow(), but that is too slow.
    this.on('readable', pipeOnReadable);

    state.flowing = true;
    process.nextTick(function() {
      flow(src);
    });
  }

  return dest;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.push"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.lmd.super_.super_.super_.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  var state = this._readableState;

  if (typeof chunk === 'string' && !state.objectMode) {
    encoding = encoding || state.defaultEncoding;
    if (encoding !== state.encoding) {
      chunk = new Buffer(chunk, encoding);
      encoding = '';
    }
  }

  return readableAddChunk(this, state, chunk, encoding, false);
}
```
- example usage
```shell
...
    var isFirstFunction = true,
        isFirstLine = true;

	/**
	 * A statement was found in the file, remember its id.
	 */
	function rememberStatement (id) {
		lines.push(id);
	};

	/**
	 * A function was found in the file, remember its id.
	 */
	function rememberFunction (id) {
		allFunctions.push(id);
...
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.read"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>read (n)](#apidoc.element.lmd.super_.super_.super_.prototype.read)
- description and source-code
```javascript
read = function (n) {
  var state = this._readableState;
  state.calledRead = true;
  var nOrig = n;
  var ret;

  if (typeof n !== 'number' || n > 0)
    state.emittedReadable = false;

  // if we're doing read(0) to trigger a readable event, but we
  // already have a bunch of data in the buffer, then just trigger
  // the 'readable' event and move on.
  if (n === 0 &&
      state.needReadable &&
      (state.length >= state.highWaterMark || state.ended)) {
    emitReadable(this);
    return null;
  }

  n = howMuchToRead(n, state);

  // if we've ended, and we're now clear, then finish it up.
  if (n === 0 && state.ended) {
    ret = null;

    // In cases where the decoder did not receive enough data
    // to produce a full chunk, then immediately received an
    // EOF, state.buffer will contain [<Buffer >, <Buffer 00 ...>].
    // howMuchToRead will see this and coerce the amount to
    // read to zero (because it's looking at the length of the
    // first <Buffer > in state.buffer), and we'll end up here.
    //
    // This can only happen via state.decoder -- no other venue
    // exists for pushing a zero-length chunk into state.buffer
    // and triggering this behavior. In this case, we return our
    // remaining data and end the stream, if appropriate.
    if (state.length > 0 && state.decoder) {
      ret = fromList(n, state);
      state.length -= ret.length;
    }

    if (state.length === 0)
      endReadable(this);

    return ret;
  }

  // All the actual chunk generation logic needs to be
  // *below* the call to _read.  The reason is that in certain
  // synthetic stream cases, such as passthrough streams, _read
  // may be a completely synchronous operation which may change
  // the state of the read buffer, providing enough data when
  // before there was *not* enough.
  //
  // So, the steps are:
  // 1. Figure out what the state of things will be after we do
  // a read from the buffer.
  //
  // 2. If that resulting state will trigger a _read, then call _read.
  // Note that this may be asynchronous, or synchronous.  Yes, it is
  // deeply ugly to write APIs this way, but that still doesn't mean
  // that the Readable class should behave improperly, as streams are
  // designed to be sync/async agnostic.
  // Take note if the _read call is sync or async (ie, if the read call
  // has returned yet), so that we know whether or not it's safe to emit
  // 'readable' etc.
  //
  // 3. Actually pull the requested chunks out of the buffer and return.

  // if we need a readable event, then we need to do some reading.
  var doRead = state.needReadable;

  // if we currently have less than the highWaterMark, then also read some
  if (state.length - n <= state.highWaterMark)
    doRead = true;

  // however, if we've ended, then there's no point, and if we're already
  // reading, then it's unnecessary.
  if (state.ended || state.reading)
    doRead = false;

  if (doRead) {
    state.reading = true;
    state.sync = true;
    // if the length is currently zero, then we *need* a readable event.
    if (state.length === 0)
      state.needReadable = true;
    // call internal read method
    this._read(state.highWaterMark);
    state.sync = false;
  }

  // If _read called its callback synchronously, then 'reading'
  // will be false, and we need to re-evaluate how much data we
  // can return to the user.
  if (doRead && !state.reading)
    n = howMuchToRead(nOrig, state);

  if (n > 0)
    ret = fromList(n, state);
  else
    ret = null;

  if (ret === null) {
    state.needReadable = true;
    n = 0;
  }

  state.length -= n;

  // If we have nothing in the buffer, then we want to know
  // as soon as we *do* get something into the buffer.
  if (state.length === 0 && !state.ended)
    state.needReadable = true;

  // If we happened to read() exactly the remaining amount in the
  // buffer, and the EOF has been seen at this point, then make sure
  // that we emit 'end' on the very next tick.
  if (state.ended && !state.endEmitted && state.length === 0)
    endReadable(this);

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.resume"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>resume ()](#apidoc.element.lmd.super_.super_.super_.prototype.resume)
- description and source-code
```javascript
resume = function () {
  emitDataEvents(this);
  this.read(0);
  this.emit('resume');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.lmd.super_.super_.super_.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function (enc) {
  if (!StringDecoder)
    StringDecoder = require('string_decoder/').StringDecoder;
  this._readableState.decoder = new StringDecoder(enc);
  this._readableState.encoding = enc;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.unpipe"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.lmd.super_.super_.super_.prototype.unpipe)
- description and source-code
```javascript
unpipe = function (dest) {
  var state = this._readableState;

  // if we're not piping anywhere, then do nothing.
  if (state.pipesCount === 0)
    return this;

  // just one destination.  most common case.
  if (state.pipesCount === 1) {
    // passed in one, but it's not the right one.
    if (dest && dest !== state.pipes)
      return this;

    if (!dest)
      dest = state.pipes;

    // got a match.
    state.pipes = null;
    state.pipesCount = 0;
    this.removeListener('readable', pipeOnReadable);
    state.flowing = false;
    if (dest)
      dest.emit('unpipe', this);
    return this;
  }

  // slow case. multiple pipe destinations.

  if (!dest) {
    // remove all.
    var dests = state.pipes;
    var len = state.pipesCount;
    state.pipes = null;
    state.pipesCount = 0;
    this.removeListener('readable', pipeOnReadable);
    state.flowing = false;

    for (var i = 0; i < len; i++)
      dests[i].emit('unpipe', this);
    return this;
  }

  // try to find the right one.
  var i = indexOf(state.pipes, dest);
  if (i === -1)
    return this;

  state.pipes.splice(i, 1);
  state.pipesCount -= 1;
  if (state.pipesCount === 1)
    state.pipes = state.pipes[0];

  dest.emit('unpipe', this);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.unshift"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.lmd.super_.super_.super_.prototype.unshift)
- description and source-code
```javascript
unshift = function (chunk) {
  var state = this._readableState;
  return readableAddChunk(this, state, chunk, '', true);
}
```
- example usage
```shell
...
        for (var moduleName in modules) {
if (!modules[moduleName].is_shortcut && !modules[moduleName].is_ignored) {
    dependsMask = modules[moduleName].depends;
    dependsConfigPath = getDependsConfigOf(modules[moduleName].path, dependsMask);
    dependsConfigPath.forEach(function (dependsConfigPath) {
        if (fileExists(dependsConfigPath)) {
            if (!usedConfigs[dependsConfigPath]) {
                configs.unshift({
                    context: 'depends config **' + dependsConfigPath + '**',
                    config: assembleLmdConfig(dependsConfigPath, flagsNames, null, usedConfigs)
                });
            }
        }
    });
}
...
```

#### <a name="apidoc.element.lmd.super_.super_.super_.prototype.wrap"></a>[function <span class="apidocSignatureSpan">lmd.super_.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.lmd.super_.super_.super_.prototype.wrap)
- description and source-code
```javascript
wrap = function (stream) {
  var state = this._readableState;
  var paused = false;

  var self = this;
  stream.on('end', function() {
    if (state.decoder && !state.ended) {
      var chunk = state.decoder.end();
      if (chunk && chunk.length)
        self.push(chunk);
    }

    self.push(null);
  });

  stream.on('data', function(chunk) {
    if (state.decoder)
      chunk = state.decoder.write(chunk);

    // don't skip over falsy values in objectMode
    //if (state.objectMode && util.isNullOrUndefined(chunk))
    if (state.objectMode && (chunk === null || chunk === undefined))
      return;
    else if (!state.objectMode && (!chunk || !chunk.length))
      return;

    var ret = self.push(chunk);
    if (!ret) {
      paused = true;
      stream.pause();
    }
  });

  // proxy all the other methods.
  // important when wrapping filters and duplexes.
  for (var i in stream) {
    if (typeof stream[i] === 'function' &&
        typeof this[i] === 'undefined') {
      this[i] = function(method) { return function() {
        return stream[method].apply(stream, arguments);
      }}(i);
    }
  }

  // proxy certain important events.
  var events = ['error', 'close', 'destroy', 'pause', 'resume'];
  forEach(events, function(ev) {
    stream.on(ev, self.emit.bind(self, ev));
  });

  // when we try to consume some more bytes, simply unpause the
  // underlying stream.
  self._read = function(n) {
    if (paused) {
      paused = false;
      stream.resume();
    }
  };

  return self;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lmd.watch"></a>[module lmd.watch](#apidoc.module.lmd.watch)

#### <a name="apidoc.element.lmd.watch.watch"></a>[function <span class="apidocSignatureSpan">lmd.</span>watch (configFile, options)](#apidoc.element.lmd.watch.watch)
- description and source-code
```javascript
watch = function (configFile, options) {
    DataStream.call(this);
    this.options = options || {};
    var self = this;

    this.configFile = configFile;

    this.init();
    this.sourceMap.readable = false;
    this.readable = false;

    // Let return instance before build
    this.watchConfig = this.compileConfig(self.configFile, self.options);

    this.makeEmptyStreamsUnreadable(this.watchConfig);

    var isFatalErrors = !this.isAllModulesExists(this.watchConfig);
    if (isFatalErrors) {
        this.readable = false;
    }
    process.nextTick(function () {
        if (!isFatalErrors) {
            if (!configFile) {
                return;
            }

            if (typeof self.watchConfig.output === 'string') {
                self.fsWatch(self.watchConfig);
                return;
            } else {
                self.log.write('ERRO'.red.inverse + ':' + '    Check your config file. "output" parameter should be a {String} eg
 "../path"'.red + '\n');
                return;
            }
        } else {
            self.printFatalErrors(self.watchConfig);
        }
        self.closeStreams();
    });
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
