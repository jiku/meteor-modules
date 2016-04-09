`lalomartins:markd` attempts to compile .md files in `node_modules/**`?

Repro steps

```
git clone https://github.com/jiku/meteor-tests.git \
& cd meteor-tests \
& git checkout packages/lalomartins:markd/1.3.2-rc.0 \
& meteor
```

Only happens with `node_modules/radium/README.md` here (code examples, moment added for comparison)

```shell
=> Errors prevented startup:

  While building the application:
  node_modules/radium/node_modules/rimraf/node_modules/glob/node_modules/minimatch/node_modules/brace-expansion/node_modules/balanced-match/README.md:31: Markdown compiler error: Expected `}}`
  ...or example, <code>{{a}</code> will match ...
  ^
  node_modules/radium/node_modules/rimraf/node_modules/glob/node_modules/minimatch/node_modules/brace-expansion/README.md:33: Markdown compiler error: Expected IDENTIFIER
  ...9;]  expand(&#39;{{A..C},{a..c}}&#39;) //...
  ^
  node_modules/radium/node_modules/inline-style-prefixer/README.md: Markdown compiler error: Expected "h1" end tag
  ...png" width=600></div> </h1> <a href="http...
  ^
  node_modules/radium/CHANGELOG.md:39: Markdown compiler error: Expected identifier, number, string, boolean, or null
  ...f={url} style={{color: &#39;gray&#39;, &#...
  ^

=> Your application has errors. Waiting for file change.
```
