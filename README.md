# meteor-modules

```
TypeError: Arguments to path.join must be strings
  at path.js:360:15
  at Array.filter (native)
  at Object.exports.join (path.js:358:36)
  at Object.pathJoin (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/static-assets/server/mini-files.js:86:16)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/import-scanner.js:53:32
  at Array.forEach (native)
  at ImportScanner.addInputFiles (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/import-scanner.js:52:11)
  at Object.fullLink (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/linker.js:959:8)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/compiler-plugin.js:673:28
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:361:18
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:354:34
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:352:23
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at Object.enterJob (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:326:26)
  at PackageSourceBatch._linkJS (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/compiler-plugin.js:672:18)
  at PackageSourceBatch.getResources (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/compiler-plugin.js:579:48)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:772:35
  at Array.forEach (native)
  at ClientTarget._emitResources (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:758:19)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:531:13
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:361:18
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:354:34
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:352:23
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at Object.enterJob (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:326:26)
  at ClientTarget.make (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:522:18)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:2178:14
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:2265:20
  at Array.forEach (native)
  at Function._.each._.forEach (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/dev_bundle/lib/node_modules/underscore/underscore.js:79:11)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:2264:7
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:273:13
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:266:29
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:264:18
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:255:23
  at [object Object]._.extend.withValue (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/fiber-helpers.js:94:14)
  at Object.capture (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/utils/buildmessage.js:254:19)
  at Object.exports.bundle (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/isobuild/bundler.js:2161:31)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/runners/run-app.js:594:36
  at time (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/tool-env/profile.js:238:28)
  at Function.run (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/tool-env/profile.js:385:12)
  at bundleApp (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/runners/run-app.js:584:34)
  at [object Object]._.extend._runOnce (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/runners/run-app.js:637:35)
  at [object Object]._.extend._fiber (/Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/runners/run-app.js:899:28)
  at /Users/jiku.dev/.meteor/packages/meteor-tool/.1.1.11-modules.3.qkkdom++os.osx.x86_64+web.browser+web.cordova/mt-os.osx.x86_64/tools/runners/run-app.js:412:12
```
