# api documentation for  [eslint (v3.19.0)](http://eslint.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint)
#### An AST-based pattern checker for JavaScript.

[![NPM](https://nodei.co/npm/eslint.png?downloads=true)](https://www.npmjs.com/package/eslint)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas C. Zakas",
        "email": "nicholas+npm@nczconsulting.com"
    },
    "bin": {
        "eslint": "./bin/eslint.js"
    },
    "bugs": {
        "url": "https://github.com/eslint/eslint/issues/"
    },
    "dependencies": {
        "babel-code-frame": "^6.16.0",
        "chalk": "^1.1.3",
        "concat-stream": "^1.5.2",
        "debug": "^2.1.1",
        "doctrine": "^2.0.0",
        "escope": "^3.6.0",
        "espree": "^3.4.0",
        "esquery": "^1.0.0",
        "estraverse": "^4.2.0",
        "esutils": "^2.0.2",
        "file-entry-cache": "^2.0.0",
        "glob": "^7.0.3",
        "globals": "^9.14.0",
        "ignore": "^3.2.0",
        "imurmurhash": "^0.1.4",
        "inquirer": "^0.12.0",
        "is-my-json-valid": "^2.10.0",
        "is-resolvable": "^1.0.0",
        "js-yaml": "^3.5.1",
        "json-stable-stringify": "^1.0.0",
        "levn": "^0.3.0",
        "lodash": "^4.0.0",
        "mkdirp": "^0.5.0",
        "natural-compare": "^1.4.0",
        "optionator": "^0.8.2",
        "path-is-inside": "^1.0.1",
        "pluralize": "^1.2.1",
        "progress": "^1.1.8",
        "require-uncached": "^1.0.2",
        "shelljs": "^0.7.5",
        "strip-bom": "^3.0.0",
        "strip-json-comments": "~2.0.1",
        "table": "^3.7.8",
        "text-table": "~0.2.0",
        "user-home": "^2.0.0"
    },
    "description": "An AST-based pattern checker for JavaScript.",
    "devDependencies": {
        "babel-polyfill": "^6.23.0",
        "babel-preset-es2015": "^6.24.0",
        "babelify": "^7.3.0",
        "beefy": "^2.1.8",
        "brfs": "1.4.3",
        "browserify": "^14.1.0",
        "chai": "^3.5.0",
        "cheerio": "^0.22.0",
        "coveralls": "^2.12.0",
        "dateformat": "^2.0.0",
        "ejs": "^2.5.6",
        "eslint-plugin-eslint-plugin": "^0.7.1",
        "eslint-plugin-node": "^4.2.1",
        "eslint-release": "^0.10.1",
        "esprima": "^3.1.3",
        "esprima-fb": "^15001.1001.0-dev-harmony-fb",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.3",
        "karma": "^1.5.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.2",
        "karma-phantomjs-launcher": "^1.0.4",
        "leche": "^2.1.2",
        "load-perf": "^0.2.0",
        "markdownlint": "^0.4.0",
        "mocha": "^3.2.0",
        "mock-fs": "^4.2.0",
        "npm-license": "^0.3.3",
        "phantomjs-prebuilt": "^2.1.14",
        "proxyquire": "^1.7.11",
        "semver": "^5.3.0",
        "shelljs-nodecli": "~0.1.1",
        "sinon": "^2.0.0",
        "temp": "^0.8.3",
        "through": "^2.3.8"
    },
    "directories": {},
    "dist": {
        "shasum": "c8fc6201c7f40dd08941b87c085767386a679acc",
        "tarball": "https://registry.npmjs.org/eslint/-/eslint-3.19.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "LICENSE",
        "README.md",
        "bin",
        "conf",
        "lib",
        "messages"
    ],
    "gitHead": "421aab44a9c167c82210bed52f68cf990b7edbea",
    "homepage": "http://eslint.org",
    "keywords": [
        "ast",
        "lint",
        "javascript",
        "ecmascript",
        "espree"
    ],
    "license": "MIT",
    "main": "./lib/api.js",
    "maintainers": [
        {
            "name": "eslint",
            "email": "nicholas+eslint@nczconsulting.com"
        },
        {
            "name": "ivolodin",
            "email": "ivolodin@gmail.com"
        },
        {
            "name": "nzakas",
            "email": "nicholas@nczconsulting.com"
        }
    ],
    "name": "eslint",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eslint/eslint.git"
    },
    "scripts": {
        "alpharelease": "node Makefile.js prerelease -- alpha",
        "betarelease": "node Makefile.js prerelease -- beta",
        "browserify": "node Makefile.js browserify",
        "check-commit": "node Makefile.js checkGitCommit",
        "ci-release": "node Makefile.js ciRelease",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "docs": "node Makefile.js docs",
        "gensite": "node Makefile.js gensite",
        "lint": "node Makefile.js lint",
        "perf": "node Makefile.js perf",
        "profile": "beefy tests/bench/bench.js --open -- -t brfs -t ./tests/bench/xform-rules.js -r espree",
        "release": "node Makefile.js release",
        "test": "node Makefile.js test"
    },
    "version": "3.19.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint](#apidoc.module.eslint)
1.  [function <span class="apidocSignatureSpan">eslint.</span>CLIEngine (options)](#apidoc.element.eslint.CLIEngine)
1.  [function <span class="apidocSignatureSpan">eslint.</span>RuleTester (testerConfig)](#apidoc.element.eslint.RuleTester)
1.  [function <span class="apidocSignatureSpan">eslint.</span>SourceCode (text, ast)](#apidoc.element.eslint.SourceCode)
1.  [function <span class="apidocSignatureSpan">eslint.</span>rule_context (ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices)](#apidoc.element.eslint.rule_context)
1.  object <span class="apidocSignatureSpan">eslint.</span>CLIEngine.prototype
1.  object <span class="apidocSignatureSpan">eslint.</span>RuleTester.prototype
1.  object <span class="apidocSignatureSpan">eslint.</span>SourceCode.prototype
1.  object <span class="apidocSignatureSpan">eslint.</span>ast_utils
1.  object <span class="apidocSignatureSpan">eslint.</span>linter
1.  object <span class="apidocSignatureSpan">eslint.</span>logging
1.  object <span class="apidocSignatureSpan">eslint.</span>options
1.  object <span class="apidocSignatureSpan">eslint.</span>rule_context.prototype
1.  object <span class="apidocSignatureSpan">eslint.</span>rules
1.  object <span class="apidocSignatureSpan">eslint.</span>timing

#### [module eslint.CLIEngine](#apidoc.module.eslint.CLIEngine)
1.  [function <span class="apidocSignatureSpan">eslint.</span>CLIEngine (options)](#apidoc.element.eslint.CLIEngine.CLIEngine)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>getErrorResults (results)](#apidoc.element.eslint.CLIEngine.getErrorResults)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>getFormatter (format)](#apidoc.element.eslint.CLIEngine.getFormatter)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>outputFixes (report)](#apidoc.element.eslint.CLIEngine.outputFixes)
1.  string <span class="apidocSignatureSpan">eslint.CLIEngine.</span>version

#### [module eslint.CLIEngine.prototype](#apidoc.module.eslint.CLIEngine.prototype)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>addPlugin (name, pluginobject)](#apidoc.element.eslint.CLIEngine.prototype.addPlugin)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>constructor (options)](#apidoc.element.eslint.CLIEngine.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>executeOnFiles (patterns)](#apidoc.element.eslint.CLIEngine.prototype.executeOnFiles)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>executeOnText (text, filename, warnIgnored)](#apidoc.element.eslint.CLIEngine.prototype.executeOnText)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>getConfigForFile (filePath)](#apidoc.element.eslint.CLIEngine.prototype.getConfigForFile)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>getFormatter (format)](#apidoc.element.eslint.CLIEngine.prototype.getFormatter)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>isPathIgnored (filePath)](#apidoc.element.eslint.CLIEngine.prototype.isPathIgnored)
1.  [function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>resolveFileGlobPatterns (patterns)](#apidoc.element.eslint.CLIEngine.prototype.resolveFileGlobPatterns)

#### [module eslint.RuleTester](#apidoc.module.eslint.RuleTester)
1.  [function <span class="apidocSignatureSpan">eslint.</span>RuleTester (testerConfig)](#apidoc.element.eslint.RuleTester.RuleTester)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.</span>describe (text, method)](#apidoc.element.eslint.RuleTester.describe)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.</span>getDefaultConfig ()](#apidoc.element.eslint.RuleTester.getDefaultConfig)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.</span>it (text, method)](#apidoc.element.eslint.RuleTester.it)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.</span>resetDefaultConfig ()](#apidoc.element.eslint.RuleTester.resetDefaultConfig)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.</span>setDefaultConfig (config)](#apidoc.element.eslint.RuleTester.setDefaultConfig)

#### [module eslint.RuleTester.prototype](#apidoc.module.eslint.RuleTester.prototype)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.prototype.</span>defineRule (name, rule)](#apidoc.element.eslint.RuleTester.prototype.defineRule)
1.  [function <span class="apidocSignatureSpan">eslint.RuleTester.prototype.</span>run (ruleName, rule, test)](#apidoc.element.eslint.RuleTester.prototype.run)

#### [module eslint.SourceCode](#apidoc.module.eslint.SourceCode)
1.  [function <span class="apidocSignatureSpan">eslint.</span>SourceCode (text, ast)](#apidoc.element.eslint.SourceCode.SourceCode)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.</span>splitLines (text)](#apidoc.element.eslint.SourceCode.splitLines)

#### [module eslint.SourceCode.prototype](#apidoc.module.eslint.SourceCode.prototype)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>constructor (text, ast)](#apidoc.element.eslint.SourceCode.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getAllComments ()](#apidoc.element.eslint.SourceCode.prototype.getAllComments)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getComments (node)](#apidoc.element.eslint.SourceCode.prototype.getComments)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getIndexFromLoc (loc)](#apidoc.element.eslint.SourceCode.prototype.getIndexFromLoc)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getJSDocComment (node)](#apidoc.element.eslint.SourceCode.prototype.getJSDocComment)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getLines ()](#apidoc.element.eslint.SourceCode.prototype.getLines)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getLocFromIndex (index)](#apidoc.element.eslint.SourceCode.prototype.getLocFromIndex)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getNodeByRangeIndex (index)](#apidoc.element.eslint.SourceCode.prototype.getNodeByRangeIndex)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getText (node, beforeCount, afterCount)](#apidoc.element.eslint.SourceCode.prototype.getText)
1.  [function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>isSpaceBetweenTokens (first, second)](#apidoc.element.eslint.SourceCode.prototype.isSpaceBetweenTokens)

#### [module eslint.ast_utils](#apidoc.module.eslint.ast_utils)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>couldBeError (node)](#apidoc.element.eslint.ast_utils.couldBeError)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>createGlobalLinebreakMatcher ()](#apidoc.element.eslint.ast_utils.createGlobalLinebreakMatcher)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getDirectivePrologue (node)](#apidoc.element.eslint.ast_utils.getDirectivePrologue)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getFunctionHeadLoc (node, sourceCode)](#apidoc.element.eslint.ast_utils.getFunctionHeadLoc)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getFunctionNameWithKind (node)](#apidoc.element.eslint.ast_utils.getFunctionNameWithKind)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getLabel (node)](#apidoc.element.eslint.ast_utils.getLabel)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getModifyingReferences (references)](#apidoc.element.eslint.ast_utils.getModifyingReferences)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getParenthesisedText (sourceCode, node)](#apidoc.element.eslint.ast_utils.getParenthesisedText)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getPrecedence (node)](#apidoc.element.eslint.ast_utils.getPrecedence)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getStaticPropertyName (node)](#apidoc.element.eslint.ast_utils.getStaticPropertyName)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getTrailingStatement (node)](#apidoc.element.eslint.ast_utils.getTrailingStatement)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getUpperFunction (node)](#apidoc.element.eslint.ast_utils.getUpperFunction)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getVariableByName (initScope, name)](#apidoc.element.eslint.ast_utils.getVariableByName)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isArrayFromMethod (node)](#apidoc.element.eslint.ast_utils.isArrayFromMethod)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isArrowToken (token)](#apidoc.element.eslint.ast_utils.isArrowToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isBreakableStatement (node)](#apidoc.element.eslint.ast_utils.isBreakableStatement)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCallee (node)](#apidoc.element.eslint.ast_utils.isCallee)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingBraceToken (token)](#apidoc.element.eslint.ast_utils.isClosingBraceToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingBracketToken (token)](#apidoc.element.eslint.ast_utils.isClosingBracketToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingParenToken (token)](#apidoc.element.eslint.ast_utils.isClosingParenToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isColonToken (token)](#apidoc.element.eslint.ast_utils.isColonToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCommaToken (token)](#apidoc.element.eslint.ast_utils.isCommaToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCommentToken (token)](#apidoc.element.eslint.ast_utils.isCommentToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDecimalInteger (node)](#apidoc.element.eslint.ast_utils.isDecimalInteger)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDefaultThisBinding (node, sourceCode)](#apidoc.element.eslint.ast_utils.isDefaultThisBinding)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDirectiveComment (node)](#apidoc.element.eslint.ast_utils.isDirectiveComment)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isES5Constructor (node)](#apidoc.element.eslint.ast_utils.isES5Constructor)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isEmptyBlock (node)](#apidoc.element.eslint.ast_utils.isEmptyBlock)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isEmptyFunction (node)](#apidoc.element.eslint.ast_utils.isEmptyFunction)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isFunction (node)](#apidoc.element.eslint.ast_utils.isFunction)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isInLoop (node)](#apidoc.element.eslint.ast_utils.isInLoop)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isKeywordToken (token)](#apidoc.element.eslint.ast_utils.isKeywordToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isLoop (node)](#apidoc.element.eslint.ast_utils.isLoop)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingBraceToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingBraceToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingBracketToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingBracketToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingParenToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingParenToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotColonToken (token)](#apidoc.element.eslint.ast_utils.isNotColonToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotCommaToken (token)](#apidoc.element.eslint.ast_utils.isNotCommaToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningBraceToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningBraceToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningBracketToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningBracketToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningParenToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningParenToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotSemicolonToken (token)](#apidoc.element.eslint.ast_utils.isNotSemicolonToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNullLiteral (node)](#apidoc.element.eslint.ast_utils.isNullLiteral)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNullOrUndefined (node)](#apidoc.element.eslint.ast_utils.isNullOrUndefined)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningBraceToken (token)](#apidoc.element.eslint.ast_utils.isOpeningBraceToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningBracketToken (token)](#apidoc.element.eslint.ast_utils.isOpeningBracketToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningParenToken (token)](#apidoc.element.eslint.ast_utils.isOpeningParenToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isParenthesised (sourceCode, node)](#apidoc.element.eslint.ast_utils.isParenthesised)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isSemicolonToken (token)](#apidoc.element.eslint.ast_utils.isSemicolonToken)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isStringLiteral (node)](#apidoc.element.eslint.ast_utils.isStringLiteral)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isSurroundedBy (val, character)](#apidoc.element.eslint.ast_utils.isSurroundedBy)
1.  [function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isTokenOnSameLine (left, right)](#apidoc.element.eslint.ast_utils.isTokenOnSameLine)
1.  object <span class="apidocSignatureSpan">eslint.ast_utils.</span>COMMENTS_IGNORE_PATTERN
1.  object <span class="apidocSignatureSpan">eslint.ast_utils.</span>LINEBREAKS
1.  object <span class="apidocSignatureSpan">eslint.ast_utils.</span>LINEBREAK_MATCHER
1.  object <span class="apidocSignatureSpan">eslint.ast_utils.</span>STATEMENT_LIST_PARENTS

#### [module eslint.linter](#apidoc.module.eslint.linter)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>defaults ()](#apidoc.element.eslint.linter.defaults)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>defineRule (ruleId, ruleModule)](#apidoc.element.eslint.linter.defineRule)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>defineRules (rulesToDefine)](#apidoc.element.eslint.linter.defineRules)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getAllComments (a, b, c, d, e)](#apidoc.element.eslint.linter.getAllComments)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getAncestors ()](#apidoc.element.eslint.linter.getAncestors)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getComments (a, b, c, d, e)](#apidoc.element.eslint.linter.getComments)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getDeclaredVariables (node)](#apidoc.element.eslint.linter.getDeclaredVariables)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getFilename ()](#apidoc.element.eslint.linter.getFilename)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.eslint.linter.getFirstToken)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getFirstTokens)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.eslint.linter.getJSDocComment)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getLastToken (a, b, c, d, e)](#apidoc.element.eslint.linter.getLastToken)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getLastTokens)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.eslint.linter.getNodeByRangeIndex)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getRules ()](#apidoc.element.eslint.linter.getRules)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getScope ()](#apidoc.element.eslint.linter.getScope)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getSource (a, b, c, d, e)](#apidoc.element.eslint.linter.getSource)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getSourceCode ()](#apidoc.element.eslint.linter.getSourceCode)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.eslint.linter.getSourceLines)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenAfter)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenBefore)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenByRangeStart)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokens)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensAfter)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensBefore)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensBetween)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>markVariableAsUsed (name)](#apidoc.element.eslint.linter.markVariableAsUsed)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>report (ruleId, severity, node, location, message, opts, fix, meta)](#apidoc.element.eslint.linter.report)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>reset ()](#apidoc.element.eslint.linter.reset)
1.  [function <span class="apidocSignatureSpan">eslint.linter.</span>verify (textOrSourceCode, config, filenameOrOptions, saveState)](#apidoc.element.eslint.linter.verify)
1.  number <span class="apidocSignatureSpan">eslint.linter.</span>_maxListeners
1.  string <span class="apidocSignatureSpan">eslint.linter.</span>version

#### [module eslint.logging](#apidoc.module.eslint.logging)
1.  [function <span class="apidocSignatureSpan">eslint.logging.</span>error ()](#apidoc.element.eslint.logging.error)
1.  [function <span class="apidocSignatureSpan">eslint.logging.</span>info ()](#apidoc.element.eslint.logging.info)

#### [module eslint.options](#apidoc.module.eslint.options)
1.  [function <span class="apidocSignatureSpan">eslint.options.</span>generateHelp (arg$)](#apidoc.element.eslint.options.generateHelp)
1.  [function <span class="apidocSignatureSpan">eslint.options.</span>generateHelpForOption (optionName)](#apidoc.element.eslint.options.generateHelpForOption)
1.  [function <span class="apidocSignatureSpan">eslint.options.</span>parse (input, arg$)](#apidoc.element.eslint.options.parse)
1.  [function <span class="apidocSignatureSpan">eslint.options.</span>parseArgv (it)](#apidoc.element.eslint.options.parseArgv)

#### [module eslint.rule_context](#apidoc.module.eslint.rule_context)
1.  [function <span class="apidocSignatureSpan">eslint.</span>rule_context (ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices)](#apidoc.element.eslint.rule_context.rule_context)

#### [module eslint.rule_context.prototype](#apidoc.module.eslint.rule_context.prototype)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getAllComments (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getAllComments)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getAncestors (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getAncestors)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getComments (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getComments)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getDeclaredVariables (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getDeclaredVariables)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFilename (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFilename)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFirstToken)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFirstTokens)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getJSDocComment)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getLastToken (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getLastToken)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getLastTokens)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getNodeByRangeIndex)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getScope (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getScope)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getSource (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getSource)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getSourceLines)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenAfter)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenBefore)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenByRangeStart)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokens)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensAfter)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensBefore)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensBetween)
1.  [function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>markVariableAsUsed (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.markVariableAsUsed)

#### [module eslint.rules](#apidoc.module.eslint.rules)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>define (ruleId, ruleModule)](#apidoc.element.eslint.rules.define)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>get (ruleId)](#apidoc.element.eslint.rules.get)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>getAllLoadedRules ()](#apidoc.element.eslint.rules.getAllLoadedRules)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>importPlugin (plugin, pluginName)](#apidoc.element.eslint.rules.importPlugin)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>load (rulesDir, cwd)](#apidoc.element.eslint.rules.load)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>testClear ()](#apidoc.element.eslint.rules.testClear)
1.  [function <span class="apidocSignatureSpan">eslint.rules.</span>testReset ()](#apidoc.element.eslint.rules.testReset)

#### [module eslint.timing](#apidoc.module.eslint.timing)
1.  boolean <span class="apidocSignatureSpan">eslint.timing.</span>enabled
1.  [function <span class="apidocSignatureSpan">eslint.timing.</span>time (key, fn)](#apidoc.element.eslint.timing.time)



# <a name="apidoc.module.eslint"></a>[module eslint](#apidoc.module.eslint)

#### <a name="apidoc.element.eslint.CLIEngine"></a>[function <span class="apidocSignatureSpan">eslint.</span>CLIEngine (options)](#apidoc.element.eslint.CLIEngine)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester"></a>[function <span class="apidocSignatureSpan">eslint.</span>RuleTester (testerConfig)](#apidoc.element.eslint.RuleTester)
- description and source-code
```javascript
function RuleTester(testerConfig) {

<span class="apidocCodeCommentSpan">    /**
     * The configuration to use for this tester. Combination of the tester
     * configuration and the default configuration.
     * @type {Object}
     */
</span>    this.testerConfig = lodash.merge(

        // we have to clone because merge uses the first argument for recipient
        lodash.cloneDeep(defaultConfig),
        testerConfig
    );

    /**
     * Rule definitions to define before tests.
     * @type {Object}
     */
    this.rules = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode"></a>[function <span class="apidocSignatureSpan">eslint.</span>SourceCode (text, ast)](#apidoc.element.eslint.SourceCode)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context"></a>[function <span class="apidocSignatureSpan">eslint.</span>rule_context (ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices)](#apidoc.element.eslint.rule_context)
- description and source-code
```javascript
class RuleContext {

<span class="apidocCodeCommentSpan">    /**
     * @param {string} ruleId The ID of the rule using this object.
     * @param {eslint} eslint The eslint object.
     * @param {number} severity The configured severity level of the rule.
     * @param {Array} options The configuration information to be added to the rule.
     * @param {Object} settings The configuration settings passed from the config file.
     * @param {Object} parserOptions The parserOptions settings passed from the config file.
     * @param {Object} parserPath The parser setting passed from the config file.
     * @param {Object} meta The metadata of the rule
     * @param {Object} parserServices The parser services for the rule.
     */
</span>    constructor(ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices) {

        // public.
        this.id = ruleId;
        this.options = options;
        this.settings = settings;
        this.parserOptions = parserOptions;
        this.parserPath = parserPath;
        this.meta = meta;

        // create a separate copy and freeze it (it's not nice to freeze other people's objects)
        this.parserServices = Object.freeze(Object.assign({}, parserServices));

        // private.
        this.eslint = eslint;
        this.severity = severity;

        Object.freeze(this);
    }

    /**
     * Passthrough to eslint.getSourceCode().
     * @returns {SourceCode} The SourceCode object for the code.
     */
    getSourceCode() {
        return this.eslint.getSourceCode();
    }

    /**
     * Passthrough to eslint.report() that automatically assigns the rule ID and severity.
     * @param {ASTNode|MessageDescriptor} nodeOrDescriptor The AST node related to the message or a message
     *      descriptor.
     * @param {Object=} location The location of the error.
     * @param {string} message The message to display to the user.
     * @param {Object} opts Optional template data which produces a formatted message
     *     with symbols being replaced by this object's values.
     * @returns {void}
     */
    report(nodeOrDescriptor, location, message, opts) {

        // check to see if it's a new style call
        if (arguments.length === 1) {
            const descriptor = nodeOrDescriptor;
            let fix = null;

            // if there's a fix specified, get it
            if (typeof descriptor.fix === "function") {
                fix = descriptor.fix(ruleFixer);
            }

            this.eslint.report(
                this.id,
                this.severity,
                descriptor.node,
                descriptor.loc || descriptor.node.loc.start,
                descriptor.message,
                descriptor.data,
                fix,
                this.meta
            );

            return;
        }

        // old style call
        this.eslint.report(
            this.id,
            this.severity,
            nodeOrDescriptor,
            location,
            message,
            opts,
            this.meta
        );
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.CLIEngine"></a>[module eslint.CLIEngine](#apidoc.module.eslint.CLIEngine)

#### <a name="apidoc.element.eslint.CLIEngine.CLIEngine"></a>[function <span class="apidocSignatureSpan">eslint.</span>CLIEngine (options)](#apidoc.element.eslint.CLIEngine.CLIEngine)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.getErrorResults"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>getErrorResults (results)](#apidoc.element.eslint.CLIEngine.getErrorResults)
- description and source-code
```javascript
getErrorResults = function (results) {
    const filtered = [];

    results.forEach(result => {
        const filteredMessages = result.messages.filter(isErrorMessage);

        if (filteredMessages.length > 0) {
            filtered.push(
                Object.assign(result, {
                    messages: filteredMessages,
                    errorCount: filteredMessages.length,
                    warningCount: 0
                })
            );
        }
    });

    return filtered;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.getFormatter"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>getFormatter (format)](#apidoc.element.eslint.CLIEngine.getFormatter)
- description and source-code
```javascript
getFormatter = function (format) {

    let formatterPath;

    // default is stylish
    format = format || "stylish";

    // only strings are valid formatters
    if (typeof format === "string") {

        // replace \ with / for Windows compatibility
        format = format.replace(/\\/g, "/");

        // if there's a slash, then it's a file
        if (format.indexOf("/") > -1) {
            const cwd = this.options ? this.options.cwd : process.cwd();

            formatterPath = path.resolve(cwd, format);
        } else {
            formatterPath = './formatters/${format}';
        }

        try {
            return require(formatterPath);
        } catch (ex) {
            ex.message = 'There was a problem loading formatter: ${formatterPath}\nError: ${ex.message}';
            throw ex;
        }

    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.outputFixes"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.</span>outputFixes (report)](#apidoc.element.eslint.CLIEngine.outputFixes)
- description and source-code
```javascript
outputFixes = function (report) {
    report.results.filter(result => result.hasOwnProperty("output")).forEach(result => {
        fs.writeFileSync(result.filePath, result.output);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.CLIEngine.prototype"></a>[module eslint.CLIEngine.prototype](#apidoc.module.eslint.CLIEngine.prototype)

#### <a name="apidoc.element.eslint.CLIEngine.prototype.addPlugin"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>addPlugin (name, pluginobject)](#apidoc.element.eslint.CLIEngine.prototype.addPlugin)
- description and source-code
```javascript
addPlugin(name, pluginobject) {
    Plugins.define(name, pluginobject);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.constructor"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>constructor (options)](#apidoc.element.eslint.CLIEngine.prototype.constructor)
- description and source-code
```javascript
function CLIEngine(options) {

    options = Object.assign(
        Object.create(null),
        defaultOptions,
        { cwd: process.cwd() },
        options
    );

<span class="apidocCodeCommentSpan">    /**
     * Stored options for this instance
     * @type {Object}
     */
</span>    this.options = options;

    const cacheFile = getCacheFile(this.options.cacheLocation || this.options.cacheFile, this.options.cwd);

    /**
     * Cache used to avoid operating on files that haven't changed since the
     * last successful execution (e.g., file passed linting with no errors and
     * no warnings).
     * @type {Object}
     */
    this._fileCache = fileEntryCache.create(cacheFile);

    // load in additional rules
    if (this.options.rulePaths) {
        const cwd = this.options.cwd;

        this.options.rulePaths.forEach(rulesdir => {
            debug('Loading rules from ${rulesdir}');
            rules.load(rulesdir, cwd);
        });
    }

    Object.keys(this.options.rules || {}).forEach(name => {
        validator.validateRuleOptions(name, this.options.rules[name], "CLI");
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.executeOnFiles"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>executeOnFiles (patterns)](#apidoc.element.eslint.CLIEngine.prototype.executeOnFiles)
- description and source-code
```javascript
executeOnFiles(patterns) {
    const results = [],
        options = this.options,
        fileCache = this._fileCache,
        configHelper = new Config(options);
    let prevConfig; // the previous configuration used

<span class="apidocCodeCommentSpan">    /**
     * Calculates the hash of the config file used to validate a given file
     * @param  {string} filename The path of the file to retrieve a config object for to calculate the hash
     * @returns {string}         the hash of the config
     */
</span>    function hashOfConfigFor(filename) {
        const config = configHelper.getConfig(filename);

        if (!prevConfig) {
            prevConfig = {};
        }

        // reuse the previously hashed config if the config hasn't changed
        if (prevConfig.config !== config) {

            /*
             * config changed so we need to calculate the hash of the config
             * and the hash of the plugins being used
             */
            prevConfig.config = config;

            const eslintVersion = pkg.version;

            prevConfig.hash = hash('${eslintVersion}_${stringify(config)}');
        }

        return prevConfig.hash;
    }

    /**
     * Executes the linter on a file defined by the 'filename'. Skips
     * unsupported file extensions and any files that are already linted.
     * @param {string} filename The resolved filename of the file to be linted
     * @param {boolean} warnIgnored always warn when a file is ignored
     * @returns {void}
     */
    function executeOnFile(filename, warnIgnored) {
        let hashOfConfig,
            descriptor;

        if (warnIgnored) {
            results.push(createIgnoreResult(filename, options.cwd));
            return;
        }

        if (options.cache) {

            /*
             * get the descriptor for this file
             * with the metadata and the flag that determines if
             * the file has changed
             */
            descriptor = fileCache.getFileDescriptor(filename);
            const meta = descriptor.meta || {};

            hashOfConfig = hashOfConfigFor(filename);

            const changed = descriptor.changed || meta.hashOfConfig !== hashOfConfig;

            if (!changed) {
                debug('Skipping file since hasn't changed: ${filename}');

                /*
                 * Add the the cached results (always will be 0 error and
                 * 0 warnings). We should not cache results for files that
                 * failed, in order to guarantee that next execution will
                 * process those files as well.
                 */
                results.push(descriptor.meta.results);

                // move to the next file
                return;
            }
        } else {
            fileCache.destroy();
        }

        debug('Processing ${filename}');

        const res = processFile(filename, configHelper, options);

        if (options.cache) {

            /*
             * if a file contains errors or warnings we don't want to
             * store the file in the cache so we can guarantee that
             * next execution will also operate on this file
             */
            if (res.errorCount > 0 || res.warningCount > 0) {
                debug('File has problems, skipping it: ${filename}');

                // remove the entry from the cache
                fileCache.removeEntry(filename);
            } else {

                /*
                 * since the file passed we store the result here
                 * TODO: check this as we might not need to store the
                 * successful runs as it will always should be 0 errors and
                 * 0 warnings.
                 */
                descriptor.meta.hashOfConfig = hashOfConfig;
                descriptor.meta.results = res;
            }
        }

        results.push(res);
    }

    const startTime = Date.now();



    patterns = this.resolveFileGlobPatterns(patterns);
    const fileList = globUtil.listFilesToProcess(patterns, options);

    fileList.forEach(fileInfo => {
        executeOnFile(fileInfo.filename, fileInfo ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.executeOnText"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>executeOnText (text, filename, warnIgnored)](#apidoc.element.eslint.CLIEngine.prototype.executeOnText)
- description and source-code
```javascript
executeOnText(text, filename, warnIgnored) {

    const results = [],
        options = this.options,
        configHelper = new Config(options),
        ignoredPaths = new IgnoredPaths(options);

    // resolve filename based on options.cwd (for reporting, ignoredPaths also resolves)
    if (filename && !path.isAbsolute(filename)) {
        filename = path.resolve(options.cwd, filename);
    }

    if (filename && ignoredPaths.contains(filename)) {
        if (warnIgnored) {
            results.push(createIgnoreResult(filename, options.cwd));
        }
    } else {
        results.push(processText(text, configHelper, filename, options.fix, options.allowInlineConfig));
    }

    const stats = calculateStatsPerRun(results);

    return {
        results,
        errorCount: stats.errorCount,
        warningCount: stats.warningCount
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.getConfigForFile"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>getConfigForFile (filePath)](#apidoc.element.eslint.CLIEngine.prototype.getConfigForFile)
- description and source-code
```javascript
getConfigForFile(filePath) {
    const configHelper = new Config(this.options);

    return configHelper.getConfig(filePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.getFormatter"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>getFormatter (format)](#apidoc.element.eslint.CLIEngine.prototype.getFormatter)
- description and source-code
```javascript
getFormatter = function (format) {

    let formatterPath;

    // default is stylish
    format = format || "stylish";

    // only strings are valid formatters
    if (typeof format === "string") {

        // replace \ with / for Windows compatibility
        format = format.replace(/\\/g, "/");

        // if there's a slash, then it's a file
        if (format.indexOf("/") > -1) {
            const cwd = this.options ? this.options.cwd : process.cwd();

            formatterPath = path.resolve(cwd, format);
        } else {
            formatterPath = './formatters/${format}';
        }

        try {
            return require(formatterPath);
        } catch (ex) {
            ex.message = 'There was a problem loading formatter: ${formatterPath}\nError: ${ex.message}';
            throw ex;
        }

    } else {
        return null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.isPathIgnored"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>isPathIgnored (filePath)](#apidoc.element.eslint.CLIEngine.prototype.isPathIgnored)
- description and source-code
```javascript
isPathIgnored(filePath) {
    const resolvedPath = path.resolve(this.options.cwd, filePath);
    const ignoredPaths = new IgnoredPaths(this.options);

    return ignoredPaths.contains(resolvedPath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.CLIEngine.prototype.resolveFileGlobPatterns"></a>[function <span class="apidocSignatureSpan">eslint.CLIEngine.prototype.</span>resolveFileGlobPatterns (patterns)](#apidoc.element.eslint.CLIEngine.prototype.resolveFileGlobPatterns)
- description and source-code
```javascript
resolveFileGlobPatterns(patterns) {
    return globUtil.resolveFileGlobPatterns(patterns, this.options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.RuleTester"></a>[module eslint.RuleTester](#apidoc.module.eslint.RuleTester)

#### <a name="apidoc.element.eslint.RuleTester.RuleTester"></a>[function <span class="apidocSignatureSpan">eslint.</span>RuleTester (testerConfig)](#apidoc.element.eslint.RuleTester.RuleTester)
- description and source-code
```javascript
function RuleTester(testerConfig) {

<span class="apidocCodeCommentSpan">    /**
     * The configuration to use for this tester. Combination of the tester
     * configuration and the default configuration.
     * @type {Object}
     */
</span>    this.testerConfig = lodash.merge(

        // we have to clone because merge uses the first argument for recipient
        lodash.cloneDeep(defaultConfig),
        testerConfig
    );

    /**
     * Rule definitions to define before tests.
     * @type {Object}
     */
    this.rules = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.describe"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.</span>describe (text, method)](#apidoc.element.eslint.RuleTester.describe)
- description and source-code
```javascript
function defaultHandler(text, method) {
    return method.apply(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.getDefaultConfig"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.</span>getDefaultConfig ()](#apidoc.element.eslint.RuleTester.getDefaultConfig)
- description and source-code
```javascript
getDefaultConfig = function () {
    return defaultConfig;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.it"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.</span>it (text, method)](#apidoc.element.eslint.RuleTester.it)
- description and source-code
```javascript
function defaultHandler(text, method) {
    return method.apply(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.resetDefaultConfig"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.</span>resetDefaultConfig ()](#apidoc.element.eslint.RuleTester.resetDefaultConfig)
- description and source-code
```javascript
resetDefaultConfig = function () {
    defaultConfig = lodash.cloneDeep(testerDefaultConfig);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.setDefaultConfig"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.</span>setDefaultConfig (config)](#apidoc.element.eslint.RuleTester.setDefaultConfig)
- description and source-code
```javascript
setDefaultConfig = function (config) {
    if (typeof config !== "object") {
        throw new Error("RuleTester.setDefaultConfig: config must be an object");
    }
    defaultConfig = config;

    // Make sure the rules object exists since it is assumed to exist later
    defaultConfig.rules = defaultConfig.rules || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.RuleTester.prototype"></a>[module eslint.RuleTester.prototype](#apidoc.module.eslint.RuleTester.prototype)

#### <a name="apidoc.element.eslint.RuleTester.prototype.defineRule"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.prototype.</span>defineRule (name, rule)](#apidoc.element.eslint.RuleTester.prototype.defineRule)
- description and source-code
```javascript
defineRule(name, rule) {
    this.rules[name] = rule;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.RuleTester.prototype.run"></a>[function <span class="apidocSignatureSpan">eslint.RuleTester.prototype.</span>run (ruleName, rule, test)](#apidoc.element.eslint.RuleTester.prototype.run)
- description and source-code
```javascript
run(ruleName, rule, test) {

    const testerConfig = this.testerConfig,
        requiredScenarios = ["valid", "invalid"],
        scenarioErrors = [],
        result = {};

    if (lodash.isNil(test) || typeof test !== "object") {
        throw new Error('Test Scenarios for rule ${ruleName} : Could not find test scenario object');
    }

    requiredScenarios.forEach(scenarioType => {
        if (lodash.isNil(test[scenarioType])) {
            scenarioErrors.push('Could not find any ${scenarioType} test scenarios');
        }
    });

    if (scenarioErrors.length > 0) {
        throw new Error([
            'Test Scenarios for rule ${ruleName} is invalid:'
        ].concat(scenarioErrors).join("\n"));
    }

<span class="apidocCodeCommentSpan">    /* eslint-disable no-shadow */
</span>
    /**
     * Run the rule for the given item
     * @param {string} ruleName name of the rule
     * @param {string|Object} item Item to run the rule against
     * @returns {Object} Eslint run result
     * @private
     */
    function runRuleForItem(ruleName, item) {
        let config = lodash.cloneDeep(testerConfig),
            code, filename, beforeAST, afterAST;

        if (typeof item === "string") {
            code = item;
        } else {
            code = item.code;

            // Assumes everything on the item is a config except for the
            // parameters used by this tester
            const itemConfig = lodash.omit(item, RuleTesterParameters);

            // Create the config object from the tester config and this item
            // specific configurations.
            config = lodash.merge(
                config,
                itemConfig
            );
        }

        if (item.filename) {
            filename = item.filename;
        }

        if (item.options) {
            const options = item.options.concat();

            options.unshift(1);
            config.rules[ruleName] = options;
        } else {
            config.rules[ruleName] = 1;
        }

        eslint.defineRule(ruleName, rule);

        const schema = validator.getRuleOptionsSchema(ruleName);

        if (schema) {
            validateSchema(schema);

            if (validateSchema.errors) {
                throw new Error([
                    'Schema for rule ${ruleName} is invalid:'
                ].concat(validateSchema.errors.map(error => '\t${error.field}: ${error.message}')).join("\n"));
            }
        }

        validator.validate(config, "rule-tester");

        /*
         * Setup AST getters.
         * The goal is to check whether or not AST was modified when
         * running the rule under test.
         */
        eslint.reset();

        eslint.on("Program", node => {
            beforeAST = cloneDeeplyExcludesParent(node);
        });

        eslint.on("Program:exit", node => {
            afterAST = node;
        });

        // Freezes rule-context properties.
        const originalGet = rules.get;

        try {
            rules.get = function(ruleId) {
                const rule = originalGet(ruleId);

                if (typeof rule === "function") {
                    return function(context) {
                        Object.freeze(context);
                        freezeDeeply(context.options);
                        freezeDeeply(context.settings);
                        freezeDeeply(context.parserOptions);

                        return rule(context);
                    };
                }
                return {
                    meta: rule.meta,
                    create(context) {
                        Object.freeze(context);
                        freezeDeeply(context.options);
                        freezeDeeply(context.settings);
                        freezeDeeply(context.parserOptions);

                        return rule.create(context);
                    }
                };

            };

            return {
                messages: eslint.verify(code, config, filename, true),
                beforeAST,
                afterAST: cloneDeeplyExcludesParent(afterAST)
            };
        } finally { ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.SourceCode"></a>[module eslint.SourceCode](#apidoc.module.eslint.SourceCode)

#### <a name="apidoc.element.eslint.SourceCode.SourceCode"></a>[function <span class="apidocSignatureSpan">eslint.</span>SourceCode (text, ast)](#apidoc.element.eslint.SourceCode.SourceCode)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.splitLines"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.</span>splitLines (text)](#apidoc.element.eslint.SourceCode.splitLines)
- description and source-code
```javascript
splitLines = function (text) {
    return text.split(astUtils.createGlobalLinebreakMatcher());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.SourceCode.prototype"></a>[module eslint.SourceCode.prototype](#apidoc.module.eslint.SourceCode.prototype)

#### <a name="apidoc.element.eslint.SourceCode.prototype.constructor"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>constructor (text, ast)](#apidoc.element.eslint.SourceCode.prototype.constructor)
- description and source-code
```javascript
function SourceCode(text, ast) {
    validate(ast);

<span class="apidocCodeCommentSpan">    /**
     * The flag to indicate that the source code has Unicode BOM.
     * @type boolean
     */
</span>    this.hasBOM = (text.charCodeAt(0) === 0xFEFF);

    /**
     * The original text source code.
     * BOM was stripped from this text.
     * @type string
     */
    this.text = (this.hasBOM ? text.slice(1) : text);

    /**
     * The parsed AST for the source code.
     * @type ASTNode
     */
    this.ast = ast;

    /**
     * The source code split into lines according to ECMA-262 specification.
     * This is done to avoid each rule needing to do so separately.
     * @type string[]
     */
    this.lines = [];
    this.lineStartIndices = [0];

    const lineEndingPattern = astUtils.createGlobalLinebreakMatcher();
    let match;

    /*
     * Previously, this was implemented using a regex that
     * matched a sequence of non-linebreak characters followed by a
     * linebreak, then adding the lengths of the matches. However,
     * this caused a catastrophic backtracking issue when the end
     * of a file contained a large number of non-newline characters.
     * To avoid this, the current implementation just matches newlines
     * and uses match.index to get the correct line start indices.
     */
    while ((match = lineEndingPattern.exec(this.text))) {
        this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1], match.index));
        this.lineStartIndices.push(match.index + match[0].length);
    }
    this.lines.push(this.text.slice(this.lineStartIndices[this.lineStartIndices.length - 1]));

    this.tokensAndComments = sortedMerge(ast.tokens, ast.comments);

    // create token store methods
    const tokenStore = new TokenStore(ast.tokens, ast.comments);

    for (const methodName of TokenStore.PUBLIC_METHODS) {
        this[methodName] = tokenStore[methodName].bind(tokenStore);
    }

    // don't allow modification of this object
    Object.freeze(this);
    Object.freeze(this.lines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getAllComments"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getAllComments ()](#apidoc.element.eslint.SourceCode.prototype.getAllComments)
- description and source-code
```javascript
getAllComments() {
    return this.ast.comments;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getComments"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getComments (node)](#apidoc.element.eslint.SourceCode.prototype.getComments)
- description and source-code
```javascript
getComments(node) {

    let leadingComments = node.leadingComments || [];
    const trailingComments = node.trailingComments || [];

<span class="apidocCodeCommentSpan">    /*
     * espree adds a "comments" array on Program nodes rather than
     * leadingComments/trailingComments. Comments are only left in the
     * Program node comments array if there is no executable code.
     */
</span>    if (node.type === "Program") {
        if (node.body.length === 0) {
            leadingComments = node.comments;
        }
    }

    return {
        leading: leadingComments,
        trailing: trailingComments
    };
}
```
- example usage
```shell
...
       return true;
   }

   // Checks '@this' in its leading comments for callbacks,
   // because callbacks don't have its JSDoc comment.
   // e.g.
   //     sinon.test(/* @this sinon.Sandbox */function() { this.spy(); });
   return sourceCode.getComments(node).leading.some(comment => thisTagPattern.test(comment.value));
}

/**
* Determines if a node is surrounded by parentheses.
* @param {SourceCode} sourceCode The ESLint source code object
* @param {ASTNode} node The node to be checked.
* @returns {boolean} True if the node is parenthesised.
...
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getIndexFromLoc"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getIndexFromLoc (loc)](#apidoc.element.eslint.SourceCode.prototype.getIndexFromLoc)
- description and source-code
```javascript
getIndexFromLoc(loc) {
    if (typeof loc !== "object" || typeof loc.line !== "number" || typeof loc.column !== "number") {
        throw new TypeError("Expected 'loc' to be an object with numeric 'line' and 'column' properties.");
    }

    if (loc.line <= 0) {
        throw new RangeError('Line number out of range (line ${loc.line} requested). Line numbers should be 1-based.');
    }

    if (loc.line > this.lineStartIndices.length) {
        throw new RangeError('Line number out of range (line ${loc.line} requested, but only ${this.lineStartIndices.length} lines
 present).');
    }

    const lineStartIndex = this.lineStartIndices[loc.line - 1];
    const lineEndIndex = loc.line === this.lineStartIndices.length ? this.text.length : this.lineStartIndices[loc.line];
    const positionIndex = lineStartIndex + loc.column;

<span class="apidocCodeCommentSpan">    /*
     * By design, getIndexFromLoc({ line: lineNum, column: 0 }) should return the start index of
     * the given line, provided that the line number is valid element of this.lines. Since the
     * last element of this.lines is an empty string for files with trailing newlines, add a
     * special case where getting the index for the first location after the end of the file
     * will return the length of the file, rather than throwing an error. This allows rules to
     * use getIndexFromLoc consistently without worrying about edge cases at the end of a file.
     */
</span>    if (
        loc.line === this.lineStartIndices.length && positionIndex > lineEndIndex ||
        loc.line < this.lineStartIndices.length && positionIndex >= lineEndIndex
    ) {
        throw new RangeError('Column number out of range (column ${loc.column} requested, but the length of line ${loc.line} is ${
lineEndIndex - lineStartIndex}).');
    }

    return positionIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getJSDocComment"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getJSDocComment (node)](#apidoc.element.eslint.SourceCode.prototype.getJSDocComment)
- description and source-code
```javascript
getJSDocComment(node) {

    let parent = node.parent;

    switch (node.type) {
        case "ClassDeclaration":
        case "FunctionDeclaration":
            if (looksLikeExport(parent)) {
                return findJSDocComment(parent.leadingComments, parent.loc.start.line);
            }
            return findJSDocComment(node.leadingComments, node.loc.start.line);

        case "ClassExpression":
            return findJSDocComment(parent.parent.leadingComments, parent.parent.loc.start.line);

        case "ArrowFunctionExpression":
        case "FunctionExpression":

            if (parent.type !== "CallExpression" && parent.type !== "NewExpression") {
                while (parent && !parent.leadingComments && !/Function/.test(parent.type) && parent.type !== "MethodDefinition" &&
parent.type !== "Property") {
                    parent = parent.parent;
                }

                return parent && (parent.type !== "FunctionDeclaration") ? findJSDocComment(parent.leadingComments, parent.loc.start
.line) : null;
            } else if (node.leadingComments) {
                return findJSDocComment(node.leadingComments, node.loc.start.line);
            }

        // falls through

        default:
            return null;
    }
}
```
- example usage
```shell
...
/**
 * Checks whether or not a node has a '@this' tag in its comments.
 * @param {ASTNode} node - A node to check.
 * @param {SourceCode} sourceCode - A SourceCode instance to get comments.
 * @returns {boolean} Whether or not the node has a '@this' tag in its comments.
 */
function hasJSDocThisTag(node, sourceCode) {
const jsdocComment = sourceCode.getJSDocComment(node);

if (jsdocComment && thisTagPattern.test(jsdocComment.value)) {
    return true;
}

// Checks '@this' in its leading comments for callbacks,
// because callbacks don't have its JSDoc comment.
...
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getLines"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getLines ()](#apidoc.element.eslint.SourceCode.prototype.getLines)
- description and source-code
```javascript
getLines() {
    return this.lines;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getLocFromIndex"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getLocFromIndex (index)](#apidoc.element.eslint.SourceCode.prototype.getLocFromIndex)
- description and source-code
```javascript
getLocFromIndex(index) {
    if (typeof index !== "number") {
        throw new TypeError("Expected 'index' to be a number.");
    }

    if (index < 0 || index > this.text.length) {
        throw new RangeError('Index out of range (requested index ${index}, but source text has length ${this.text.length}).');
    }

<span class="apidocCodeCommentSpan">    /*
     * For an argument of this.text.length, return the location one "spot" past the last character
     * of the file. If the last character is a linebreak, the location will be column 0 of the next
     * line; otherwise, the location will be in the next column on the same line.
     *
     * See getIndexFromLoc for the motivation for this special case.
     */
</span>    if (index === this.text.length) {
        return { line: this.lines.length, column: this.lines[this.lines.length - 1].length };
    }

    /*
     * To figure out which line rangeIndex is on, determine the last index at which rangeIndex could
     * be inserted into lineIndices to keep the list sorted.
     */
    const lineNumber = lodash.sortedLastIndex(this.lineStartIndices, index);

    return { line: lineNumber, column: index - this.lineStartIndices[lineNumber - 1] };

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getNodeByRangeIndex"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getNodeByRangeIndex (index)](#apidoc.element.eslint.SourceCode.prototype.getNodeByRangeIndex)
- description and source-code
```javascript
getNodeByRangeIndex(index) {
    let result = null,
        resultParent = null;
    const traverser = new Traverser();

    traverser.traverse(this.ast, {
        enter(node, parent) {
            if (node.range[0] <= index && index < node.range[1]) {
                result = node;
                resultParent = parent;
            } else {
                this.skip();
            }
        },
        leave(node) {
            if (node === result) {
                this.break();
            }
        }
    });

    return result ? Object.assign({ parent: resultParent }, result) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.getText"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>getText (node, beforeCount, afterCount)](#apidoc.element.eslint.SourceCode.prototype.getText)
- description and source-code
```javascript
getText(node, beforeCount, afterCount) {
    if (node) {
        return this.text.slice(Math.max(node.range[0] - (beforeCount || 0), 0),
            node.range[1] + (afterCount || 0));
    }
    return this.text;


}
```
- example usage
```shell
...
    return {
        start: Object.assign({}, start),
        end: Object.assign({}, end)
    };
},

/**
* Gets the parenthesized text of a node. This is similar to sourceCode.getText(node), but it also includes any parentheses
* surrounding the node.
* @param {SourceCode} sourceCode The source code object
* @param {ASTNode} node An expression node
* @returns {string} The text representing the node, with all surrounding parentheses included
*/
getParenthesisedText(sourceCode, node) {
    let leftToken = sourceCode.getFirstToken(node);
...
```

#### <a name="apidoc.element.eslint.SourceCode.prototype.isSpaceBetweenTokens"></a>[function <span class="apidocSignatureSpan">eslint.SourceCode.prototype.</span>isSpaceBetweenTokens (first, second)](#apidoc.element.eslint.SourceCode.prototype.isSpaceBetweenTokens)
- description and source-code
```javascript
isSpaceBetweenTokens(first, second) {
    const text = this.text.slice(first.range[1], second.range[0]);

    return /\s/.test(text.replace(/\/\*.*?\*\//g, ""));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.ast_utils"></a>[module eslint.ast_utils](#apidoc.module.eslint.ast_utils)

#### <a name="apidoc.element.eslint.ast_utils.couldBeError"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>couldBeError (node)](#apidoc.element.eslint.ast_utils.couldBeError)
- description and source-code
```javascript
couldBeError(node) {
    switch (node.type) {
        case "Identifier":
        case "CallExpression":
        case "NewExpression":
        case "MemberExpression":
        case "TaggedTemplateExpression":
        case "YieldExpression":
        case "AwaitExpression":
            return true; // possibly an error object.

        case "AssignmentExpression":
            return module.exports.couldBeError(node.right);

        case "SequenceExpression": {
            const exprs = node.expressions;

            return exprs.length !== 0 && module.exports.couldBeError(exprs[exprs.length - 1]);
        }

        case "LogicalExpression":
            return module.exports.couldBeError(node.left) || module.exports.couldBeError(node.right);

        case "ConditionalExpression":
            return module.exports.couldBeError(node.consequent) || module.exports.couldBeError(node.alternate);

        default:
            return false;
    }
}
```
- example usage
```shell
...
case "MemberExpression":
case "TaggedTemplateExpression":
case "YieldExpression":
case "AwaitExpression":
    return true; // possibly an error object.

case "AssignmentExpression":
    return module.exports.couldBeError(node.right);

case "SequenceExpression": {
    const exprs = node.expressions;

    return exprs.length !== 0 && module.exports.couldBeError(exprs[exprs.length - 1]);
}
...
```

#### <a name="apidoc.element.eslint.ast_utils.createGlobalLinebreakMatcher"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>createGlobalLinebreakMatcher ()](#apidoc.element.eslint.ast_utils.createGlobalLinebreakMatcher)
- description and source-code
```javascript
function createGlobalLinebreakMatcher() {
    return new RegExp(LINEBREAK_MATCHER.source, "g");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getDirectivePrologue"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getDirectivePrologue (node)](#apidoc.element.eslint.ast_utils.getDirectivePrologue)
- description and source-code
```javascript
getDirectivePrologue(node) {
    const directives = [];

    // Directive prologues only occur at the top of files or functions.
    if (
        node.type === "Program" ||
        node.type === "FunctionDeclaration" ||
        node.type === "FunctionExpression" ||

        // Do not check arrow functions with implicit return.
        // '() => "use strict";' returns the string '"use strict"'.
        (node.type === "ArrowFunctionExpression" && node.body.type === "BlockStatement")
    ) {
        const statements = node.type === "Program" ? node.body : node.body.body;

        for (const statement of statements) {
            if (
                statement.type === "ExpressionStatement" &&
                statement.expression.type === "Literal"
            ) {
                directives.push(statement);
            } else {
                break;
            }
        }
    }

    return directives;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getFunctionHeadLoc"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getFunctionHeadLoc (node, sourceCode)](#apidoc.element.eslint.ast_utils.getFunctionHeadLoc)
- description and source-code
```javascript
getFunctionHeadLoc(node, sourceCode) {
    const parent = node.parent;
    let start = null;
    let end = null;

    if (node.type === "ArrowFunctionExpression") {
        const arrowToken = sourceCode.getTokenBefore(node.body, isArrowToken);

        start = arrowToken.loc.start;
        end = arrowToken.loc.end;
    } else if (parent.type === "Property" || parent.type === "MethodDefinition") {
        start = parent.loc.start;
        end = getOpeningParenOfParams(node, sourceCode).loc.start;
    } else {
        start = node.loc.start;
        end = getOpeningParenOfParams(node, sourceCode).loc.start;
    }

    return {
        start: Object.assign({}, start),
        end: Object.assign({}, end)
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getFunctionNameWithKind"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getFunctionNameWithKind (node)](#apidoc.element.eslint.ast_utils.getFunctionNameWithKind)
- description and source-code
```javascript
getFunctionNameWithKind(node) {
    const parent = node.parent;
    const tokens = [];

    if (parent.type === "MethodDefinition" && parent.static) {
        tokens.push("static");
    }
    if (node.async) {
        tokens.push("async");
    }
    if (node.generator) {
        tokens.push("generator");
    }

    if (node.type === "ArrowFunctionExpression") {
        tokens.push("arrow", "function");
    } else if (parent.type === "Property" || parent.type === "MethodDefinition") {
        if (parent.kind === "constructor") {
            return "constructor";
        } else if (parent.kind === "get") {
            tokens.push("getter");
        } else if (parent.kind === "set") {
            tokens.push("setter");
        } else {
            tokens.push("method");
        }
    } else {
        tokens.push("function");
    }

    if (node.id) {
        tokens.push(''${node.id.name}'');
    } else {
        const name = module.exports.getStaticPropertyName(parent);

        if (name) {
            tokens.push(''${name}'');
        }
    }

    return tokens.join(" ");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getLabel"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getLabel (node)](#apidoc.element.eslint.ast_utils.getLabel)
- description and source-code
```javascript
getLabel(node) {
    if (node.parent.type === "LabeledStatement") {
        return node.parent.label.name;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getModifyingReferences"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getModifyingReferences (references)](#apidoc.element.eslint.ast_utils.getModifyingReferences)
- description and source-code
```javascript
getModifyingReferences(references) {
    return references.filter(isModifyingReference);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getParenthesisedText"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getParenthesisedText (sourceCode, node)](#apidoc.element.eslint.ast_utils.getParenthesisedText)
- description and source-code
```javascript
getParenthesisedText(sourceCode, node) {
    let leftToken = sourceCode.getFirstToken(node);
    let rightToken = sourceCode.getLastToken(node);

    while (
        sourceCode.getTokenBefore(leftToken) &&
        sourceCode.getTokenBefore(leftToken).type === "Punctuator" &&
        sourceCode.getTokenBefore(leftToken).value === "(" &&
        sourceCode.getTokenAfter(rightToken) &&
        sourceCode.getTokenAfter(rightToken).type === "Punctuator" &&
        sourceCode.getTokenAfter(rightToken).value === ")"
    ) {
        leftToken = sourceCode.getTokenBefore(leftToken);
        rightToken = sourceCode.getTokenAfter(rightToken);
    }

    return sourceCode.getText().slice(leftToken.range[0], rightToken.range[1]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getPrecedence"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getPrecedence (node)](#apidoc.element.eslint.ast_utils.getPrecedence)
- description and source-code
```javascript
getPrecedence(node) {
    switch (node.type) {
        case "SequenceExpression":
            return 0;

        case "AssignmentExpression":
        case "ArrowFunctionExpression":
        case "YieldExpression":
            return 1;

        case "ConditionalExpression":
            return 3;

        case "LogicalExpression":
            switch (node.operator) {
                case "||":
                    return 4;
                case "&&":
                    return 5;

                // no default
            }

<span class="apidocCodeCommentSpan">            /* falls through */
</span>
        case "BinaryExpression":

            switch (node.operator) {
                case "|":
                    return 6;
                case "^":
                    return 7;
                case "&":
                    return 8;
                case "==":
                case "!=":
                case "===":
                case "!==":
                    return 9;
                case "<":
                case "<=":
                case ">":
                case ">=":
                case "in":
                case "instanceof":
                    return 10;
                case "<<":
                case ">>":
                case ">>>":
                    return 11;
                case "+":
                case "-":
                    return 12;
                case "*":
                case "/":
                case "%":
                    return 13;
                case "**":
                    return 15;

                // no default
            }

            /* falls through */

        case "UnaryExpression":
        case "AwaitExpression":
            return 16;

        case "UpdateExpression":
            return 17;

        case "CallExpression":

            // IIFE is allowed to have parens in any position (#655)
            if (node.callee.type === "FunctionExpression") {
                return -1;
            }
            return 18;

        case "NewExpression":
            return 19;

        // no default
    }
    return 20;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getStaticPropertyName"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getStaticPropertyName (node)](#apidoc.element.eslint.ast_utils.getStaticPropertyName)
- description and source-code
```javascript
getStaticPropertyName(node) {
    let prop;

    switch (node && node.type) {
        case "Property":
        case "MethodDefinition":
            prop = node.key;
            break;

        case "MemberExpression":
            prop = node.property;
            break;

        // no default
    }

    switch (prop && prop.type) {
        case "Literal":
            return String(prop.value);

        case "TemplateLiteral":
            if (prop.expressions.length === 0 && prop.quasis.length === 1) {
                return prop.quasis[0].value.cooked;
            }
            break;

        case "Identifier":
            if (!node.computed) {
                return prop.name;
            }
            break;

        // no default
    }

    return null;
}
```
- example usage
```shell
...
} else {
    tokens.push("function");
}

if (node.id) {
    tokens.push(''${node.id.name}'');
} else {
    const name = module.exports.getStaticPropertyName(parent);

    if (name) {
        tokens.push(''${name}'');
    }
}

return tokens.join(" ");
...
```

#### <a name="apidoc.element.eslint.ast_utils.getTrailingStatement"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getTrailingStatement (node)](#apidoc.element.eslint.ast_utils.getTrailingStatement)
- description and source-code
```javascript
function trailingStatement(node) {
    switch (node.type) {
    case 'IfStatement':
        if (node.alternate != null) {
            return node.alternate;
        }
        return node.consequent;

    case 'LabeledStatement':
    case 'ForStatement':
    case 'ForInStatement':
    case 'WhileStatement':
    case 'WithStatement':
        return node.body;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getUpperFunction"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getUpperFunction (node)](#apidoc.element.eslint.ast_utils.getUpperFunction)
- description and source-code
```javascript
function getUpperFunction(node) {
    while (node) {
        if (anyFunctionPattern.test(node.type)) {
            return node;
        }
        node = node.parent;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.getVariableByName"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>getVariableByName (initScope, name)](#apidoc.element.eslint.ast_utils.getVariableByName)
- description and source-code
```javascript
getVariableByName(initScope, name) {
    let scope = initScope;

    while (scope) {
        const variable = scope.set.get(name);

        if (variable) {
            return variable;
        }

        scope = scope.upper;
    }

    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isArrayFromMethod"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isArrayFromMethod (node)](#apidoc.element.eslint.ast_utils.isArrayFromMethod)
- description and source-code
```javascript
function isArrayFromMethod(node) {
    return (
        node.type === "MemberExpression" &&
        node.object.type === "Identifier" &&
        arrayOrTypedArrayPattern.test(node.object.name) &&
        node.property.type === "Identifier" &&
        node.property.name === "from" &&
        node.computed === false
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isArrowToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isArrowToken (token)](#apidoc.element.eslint.ast_utils.isArrowToken)
- description and source-code
```javascript
function isArrowToken(token) {
    return token.value === "=>" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isBreakableStatement"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isBreakableStatement (node)](#apidoc.element.eslint.ast_utils.isBreakableStatement)
- description and source-code
```javascript
isBreakableStatement(node) {
    return breakableTypePattern.test(node.type);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isCallee"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCallee (node)](#apidoc.element.eslint.ast_utils.isCallee)
- description and source-code
```javascript
function isCallee(node) {
    return node.parent.type === "CallExpression" && node.parent.callee === node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isClosingBraceToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingBraceToken (token)](#apidoc.element.eslint.ast_utils.isClosingBraceToken)
- description and source-code
```javascript
function isClosingBraceToken(token) {
    return token.value === "}" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isClosingBracketToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingBracketToken (token)](#apidoc.element.eslint.ast_utils.isClosingBracketToken)
- description and source-code
```javascript
function isClosingBracketToken(token) {
    return token.value === "]" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isClosingParenToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isClosingParenToken (token)](#apidoc.element.eslint.ast_utils.isClosingParenToken)
- description and source-code
```javascript
function isClosingParenToken(token) {
    return token.value === ")" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isColonToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isColonToken (token)](#apidoc.element.eslint.ast_utils.isColonToken)
- description and source-code
```javascript
function isColonToken(token) {
    return token.value === ":" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isCommaToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCommaToken (token)](#apidoc.element.eslint.ast_utils.isCommaToken)
- description and source-code
```javascript
function isCommaToken(token) {
    return token.value === "," && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isCommentToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isCommentToken (token)](#apidoc.element.eslint.ast_utils.isCommentToken)
- description and source-code
```javascript
function isCommentToken(token) {
    return token.type === "Line" || token.type === "Block" || token.type === "Shebang";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isDecimalInteger"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDecimalInteger (node)](#apidoc.element.eslint.ast_utils.isDecimalInteger)
- description and source-code
```javascript
isDecimalInteger(node) {
    return node.type === "Literal" && typeof node.value === "number" && /^(0|[1-9]\d*)$/.test(node.raw);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isDefaultThisBinding"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDefaultThisBinding (node, sourceCode)](#apidoc.element.eslint.ast_utils.isDefaultThisBinding)
- description and source-code
```javascript
isDefaultThisBinding(node, sourceCode) {
    if (isES5Constructor(node) || hasJSDocThisTag(node, sourceCode)) {
        return false;
    }
    const isAnonymous = node.id === null;

    while (node) {
        const parent = node.parent;

        switch (parent.type) {

<span class="apidocCodeCommentSpan">            /*
             * Looks up the destination.
             * e.g., obj.foo = nativeFoo || function foo() { ... };
             */
</span>            case "LogicalExpression":
            case "ConditionalExpression":
                node = parent;
                break;

            // If the upper function is IIFE, checks the destination of the return value.
            // e.g.
            //   obj.foo = (function() {
            //     // setup...
            //     return function foo() { ... };
            //   })();
            case "ReturnStatement": {
                const func = getUpperFunction(parent);

                if (func === null || !isCallee(func)) {
                    return true;
                }
                node = func.parent;
                break;
            }

            // e.g.
            //   var obj = { foo() { ... } };
            //   var obj = { foo: function() { ... } };
            //   class A { constructor() { ... } }
            //   class A { foo() { ... } }
            //   class A { get foo() { ... } }
            //   class A { set foo() { ... } }
            //   class A { static foo() { ... } }
            case "Property":
            case "MethodDefinition":
                return parent.value !== node;

            // e.g.
            //   obj.foo = function foo() { ... };
            //   Foo = function() { ... };
            //   [obj.foo = function foo() { ... }] = a;
            //   [Foo = function() { ... }] = a;
            case "AssignmentExpression":
            case "AssignmentPattern":
                if (parent.right === node) {
                    if (parent.left.type === "MemberExpression") {
                        return false;
                    }
                    if (isAnonymous &&
                        parent.left.type === "Identifier" &&
                        startsWithUpperCase(parent.left.name)
                    ) {
                        return false;
                    }
                }
                return true;

            // e.g.
            //   var Foo = function() { ... };
            case "VariableDeclarator":
                return !(
                    isAnonymous &&
                    parent.init === node &&
                    parent.id.type === "Identifier" &&
                    startsWithUpperCase(parent.id.name)
                );

            // e.g.
            //   var foo = function foo() { ... }.bind(obj);
            //   (function foo() { ... }).call(obj);
            //   (function foo() { ... }).apply(obj, []);
            case "MemberExpression":
                return (
                    parent.object !== node ||
                    parent.property.type !== "Identifier" ||
                    !bindOrCallOrApplyPattern.test(parent.property.name) ||
                    !isCallee(parent) ||
                    parent.parent.arguments.length === 0 ||
                    isNullOrUndefined(parent.parent.arguments[0])
                );

            // e.g.
            //   Reflect.apply(function() {}, obj, []);
            //   Array.from([], function() {}, obj);
            //   list.forEach(function() {}, obj);
            case "CallExpression":
                if (isReflectApply(parent.callee)) {
                    return (
                        parent.arguments.length !== 3 ||
                        parent.arguments[0] !== node ||
                        isNullOrUndefined(parent.arguments[1])
                    );
                }
                if (isArrayFromMethod(parent.callee)) {
                    return (
                        parent.arguments.length !== 3 ||
                        parent.arguments[1] !== node ||
                        isNullOrUndefined(parent.arguments[2])
                    );
                } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isDirectiveComment"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isDirectiveComment (node)](#apidoc.element.eslint.ast_utils.isDirectiveComment)
- description and source-code
```javascript
isDirectiveComment(node) {
    const comment = node.value.trim();

    return (
        node.type === "Line" && comment.indexOf("eslint-") === 0 ||
        node.type === "Block" && (
            comment.indexOf("global ") === 0 ||
            comment.indexOf("eslint ") === 0 ||
            comment.indexOf("eslint-") === 0
        )
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isES5Constructor"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isES5Constructor (node)](#apidoc.element.eslint.ast_utils.isES5Constructor)
- description and source-code
```javascript
function isES5Constructor(node) {
    return (node.id && startsWithUpperCase(node.id.name));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isEmptyBlock"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isEmptyBlock (node)](#apidoc.element.eslint.ast_utils.isEmptyBlock)
- description and source-code
```javascript
isEmptyBlock(node) {
    return Boolean(node && node.type === "BlockStatement" && node.body.length === 0);
}
```
- example usage
```shell
...
/**
 * Checks whether the given node is an empty function node or not.
 *
 * @param {ASTNode|null} node - The node to check.
 * @returns {boolean} 'true' if the node is an empty function.
 */
isEmptyFunction(node) {
    return isFunction(node) && module.exports.isEmptyBlock(node.body);
},

/**
 * Gets the property name of a given node.
 * The node can be a MemberExpression, a Property, or a MethodDefinition.
 *
 * If the name is dynamic, this returns 'null'.
...
```

#### <a name="apidoc.element.eslint.ast_utils.isEmptyFunction"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isEmptyFunction (node)](#apidoc.element.eslint.ast_utils.isEmptyFunction)
- description and source-code
```javascript
isEmptyFunction(node) {
    return isFunction(node) && module.exports.isEmptyBlock(node.body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isFunction"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isFunction (node)](#apidoc.element.eslint.ast_utils.isFunction)
- description and source-code
```javascript
function isFunction(node) {
    return Boolean(node && anyFunctionPattern.test(node.type));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isInLoop"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isInLoop (node)](#apidoc.element.eslint.ast_utils.isInLoop)
- description and source-code
```javascript
function isInLoop(node) {
    while (node && !isFunction(node)) {
        if (isLoop(node)) {
            return true;
        }

        node = node.parent;
    }

    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isKeywordToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isKeywordToken (token)](#apidoc.element.eslint.ast_utils.isKeywordToken)
- description and source-code
```javascript
function isKeywordToken(token) {
    return token.type === "Keyword";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isLoop"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isLoop (node)](#apidoc.element.eslint.ast_utils.isLoop)
- description and source-code
```javascript
function isLoop(node) {
    return Boolean(node && anyLoopPattern.test(node.type));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotClosingBraceToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingBraceToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingBraceToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotClosingBracketToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingBracketToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingBracketToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotClosingParenToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotClosingParenToken (token)](#apidoc.element.eslint.ast_utils.isNotClosingParenToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotColonToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotColonToken (token)](#apidoc.element.eslint.ast_utils.isNotColonToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotCommaToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotCommaToken (token)](#apidoc.element.eslint.ast_utils.isNotCommaToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotOpeningBraceToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningBraceToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningBraceToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotOpeningBracketToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningBracketToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningBracketToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotOpeningParenToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotOpeningParenToken (token)](#apidoc.element.eslint.ast_utils.isNotOpeningParenToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNotSemicolonToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNotSemicolonToken (token)](#apidoc.element.eslint.ast_utils.isNotSemicolonToken)
- description and source-code
```javascript
token => !f(token)
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isNullLiteral"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNullLiteral (node)](#apidoc.element.eslint.ast_utils.isNullLiteral)
- description and source-code
```javascript
isNullLiteral(node) {

<span class="apidocCodeCommentSpan">    /*
     * Checking 'node.value === null' does not guarantee that a literal is a null literal.
     * When parsing values that cannot be represented in the current environment (e.g. unicode
     * regexes in Node 4), 'node.value' is set to 'null' because it wouldn't be possible to
     * set 'node.value' to a unicode regex. To make sure a literal is actually 'null', check
     * 'node.regex' instead. Also see: https://github.com/eslint/eslint/issues/8020
     */
</span>    return node.type === "Literal" && node.value === null && !node.regex;
}
```
- example usage
```shell
...
* Checks whether or not a node is 'null' or 'undefined'.
* @param {ASTNode} node - A node to check.
* @returns {boolean} Whether or not the node is a 'null' or 'undefined'.
* @public
*/
function isNullOrUndefined(node) {
   return (
       module.exports.isNullLiteral(node) ||
       (node.type === "Identifier" && node.name === "undefined") ||
       (node.type === "UnaryExpression" && node.operator === "void")
   );
}

/**
* Checks whether or not a node is callee.
...
```

#### <a name="apidoc.element.eslint.ast_utils.isNullOrUndefined"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isNullOrUndefined (node)](#apidoc.element.eslint.ast_utils.isNullOrUndefined)
- description and source-code
```javascript
function isNullOrUndefined(node) {
    return (
        module.exports.isNullLiteral(node) ||
        (node.type === "Identifier" && node.name === "undefined") ||
        (node.type === "UnaryExpression" && node.operator === "void")
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isOpeningBraceToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningBraceToken (token)](#apidoc.element.eslint.ast_utils.isOpeningBraceToken)
- description and source-code
```javascript
function isOpeningBraceToken(token) {
    return token.value === "{" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isOpeningBracketToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningBracketToken (token)](#apidoc.element.eslint.ast_utils.isOpeningBracketToken)
- description and source-code
```javascript
function isOpeningBracketToken(token) {
    return token.value === "[" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isOpeningParenToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isOpeningParenToken (token)](#apidoc.element.eslint.ast_utils.isOpeningParenToken)
- description and source-code
```javascript
function isOpeningParenToken(token) {
    return token.value === "(" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isParenthesised"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isParenthesised (sourceCode, node)](#apidoc.element.eslint.ast_utils.isParenthesised)
- description and source-code
```javascript
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isSemicolonToken"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isSemicolonToken (token)](#apidoc.element.eslint.ast_utils.isSemicolonToken)
- description and source-code
```javascript
function isSemicolonToken(token) {
    return token.value === ";" && token.type === "Punctuator";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isStringLiteral"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isStringLiteral (node)](#apidoc.element.eslint.ast_utils.isStringLiteral)
- description and source-code
```javascript
isStringLiteral(node) {
    return (
        (node.type === "Literal" && typeof node.value === "string") ||
        node.type === "TemplateLiteral"
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isSurroundedBy"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isSurroundedBy (val, character)](#apidoc.element.eslint.ast_utils.isSurroundedBy)
- description and source-code
```javascript
isSurroundedBy(val, character) {
    return val[0] === character && val[val.length - 1] === character;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.ast_utils.isTokenOnSameLine"></a>[function <span class="apidocSignatureSpan">eslint.ast_utils.</span>isTokenOnSameLine (left, right)](#apidoc.element.eslint.ast_utils.isTokenOnSameLine)
- description and source-code
```javascript
isTokenOnSameLine(left, right) {
    return left.loc.end.line === right.loc.start.line;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.linter"></a>[module eslint.linter](#apidoc.module.eslint.linter)

#### <a name="apidoc.element.eslint.linter.defaults"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>defaults ()](#apidoc.element.eslint.linter.defaults)
- description and source-code
```javascript
defaults = function () {
    return require("../conf/eslint-recommended");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.defineRule"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>defineRule (ruleId, ruleModule)](#apidoc.element.eslint.linter.defineRule)
- description and source-code
```javascript
defineRule = function (ruleId, ruleModule) {
    rules.define(ruleId, ruleModule);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.defineRules"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>defineRules (rulesToDefine)](#apidoc.element.eslint.linter.defineRules)
- description and source-code
```javascript
defineRules = function (rulesToDefine) {
    Object.getOwnPropertyNames(rulesToDefine).forEach(ruleId => {
        defineRule(ruleId, rulesToDefine[ruleId]);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getAllComments"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getAllComments (a, b, c, d, e)](#apidoc.element.eslint.linter.getAllComments)
- description and source-code
```javascript
getAllComments = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getAncestors"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getAncestors ()](#apidoc.element.eslint.linter.getAncestors)
- description and source-code
```javascript
getAncestors = function () {
    return traverser.parents();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getComments"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getComments (a, b, c, d, e)](#apidoc.element.eslint.linter.getComments)
- description and source-code
```javascript
getComments = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
       return true;
   }

   // Checks '@this' in its leading comments for callbacks,
   // because callbacks don't have its JSDoc comment.
   // e.g.
   //     sinon.test(/* @this sinon.Sandbox */function() { this.spy(); });
   return sourceCode.getComments(node).leading.some(comment => thisTagPattern.test(comment.value));
}

/**
* Determines if a node is surrounded by parentheses.
* @param {SourceCode} sourceCode The ESLint source code object
* @param {ASTNode} node The node to be checked.
* @returns {boolean} True if the node is parenthesised.
...
```

#### <a name="apidoc.element.eslint.linter.getDeclaredVariables"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getDeclaredVariables (node)](#apidoc.element.eslint.linter.getDeclaredVariables)
- description and source-code
```javascript
getDeclaredVariables = function (node) {
    return (scopeManager && scopeManager.getDeclaredVariables(node)) || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getFilename"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getFilename ()](#apidoc.element.eslint.linter.getFilename)
- description and source-code
```javascript
getFilename = function () {
    if (typeof currentFilename === "string") {
        return currentFilename;
    }
    return "<input>";

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getFirstToken"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.eslint.linter.getFirstToken)
- description and source-code
```javascript
getFirstToken = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
* @param {ASTNode} node - The function node to get.
* @param {SourceCode} sourceCode - The source code object to get tokens.
* @returns {Token} '(' token.
*/
function getOpeningParenOfParams(node, sourceCode) {
   return node.id
       ? sourceCode.getTokenAfter(node.id, isOpeningParenToken)
       : sourceCode.getFirstToken(node, isOpeningParenToken);
}

/**
* Creates a version of the LINEBREAK_MATCHER regex with the global flag.
* Global regexes are mutable, so this needs to be a function instead of a constant.
* @returns {RegExp} A global regular expression that matches line terminators
*/
...
```

#### <a name="apidoc.element.eslint.linter.getFirstTokens"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getFirstTokens)
- description and source-code
```javascript
getFirstTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getJSDocComment"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.eslint.linter.getJSDocComment)
- description and source-code
```javascript
getJSDocComment = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
/**
 * Checks whether or not a node has a '@this' tag in its comments.
 * @param {ASTNode} node - A node to check.
 * @param {SourceCode} sourceCode - A SourceCode instance to get comments.
 * @returns {boolean} Whether or not the node has a '@this' tag in its comments.
 */
function hasJSDocThisTag(node, sourceCode) {
const jsdocComment = sourceCode.getJSDocComment(node);

if (jsdocComment && thisTagPattern.test(jsdocComment.value)) {
    return true;
}

// Checks '@this' in its leading comments for callbacks,
// because callbacks don't have its JSDoc comment.
...
```

#### <a name="apidoc.element.eslint.linter.getLastToken"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getLastToken (a, b, c, d, e)](#apidoc.element.eslint.linter.getLastToken)
- description and source-code
```javascript
getLastToken = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
    * surrounding the node.
    * @param {SourceCode} sourceCode The source code object
    * @param {ASTNode} node An expression node
    * @returns {string} The text representing the node, with all surrounding parentheses included
    */
    getParenthesisedText(sourceCode, node) {
let leftToken = sourceCode.getFirstToken(node);
let rightToken = sourceCode.getLastToken(node);

while (
    sourceCode.getTokenBefore(leftToken) &&
    sourceCode.getTokenBefore(leftToken).type === "Punctuator" &&
    sourceCode.getTokenBefore(leftToken).value === "(" &&
    sourceCode.getTokenAfter(rightToken) &&
    sourceCode.getTokenAfter(rightToken).type === "Punctuator" &&
...
```

#### <a name="apidoc.element.eslint.linter.getLastTokens"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getLastTokens)
- description and source-code
```javascript
getLastTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getNodeByRangeIndex"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.eslint.linter.getNodeByRangeIndex)
- description and source-code
```javascript
getNodeByRangeIndex = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getRules"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getRules ()](#apidoc.element.eslint.linter.getRules)
- description and source-code
```javascript
getRules = function () {
    return rules.getAllLoadedRules();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getScope"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getScope ()](#apidoc.element.eslint.linter.getScope)
- description and source-code
```javascript
getScope = function () {
    const parents = traverser.parents();

    // Don't do this for Program nodes - they have no parents
    if (parents.length) {

        // if current node introduces a scope, add it to the list
        const current = traverser.current();

        if (currentConfig.parserOptions.ecmaVersion >= 6) {
            if (["BlockStatement", "SwitchStatement", "CatchClause", "FunctionDeclaration", "FunctionExpression", "ArrowFunctionExpression
"].indexOf(current.type) >= 0) {
                parents.push(current);
            }
        } else {
            if (["FunctionDeclaration", "FunctionExpression", "ArrowFunctionExpression"].indexOf(current.type) >= 0) {
                parents.push(current);
            }
        }

        // Ascend the current node's parents
        for (let i = parents.length - 1; i >= 0; --i) {

            // Get the innermost scope
            const scope = scopeManager.acquire(parents[i], true);

            if (scope) {
                if (scope.type === "function-expression-name") {
                    return scope.childScopes[0];
                }
                return scope;

            }

        }

    }

    return currentScopes[0];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getSource"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getSource (a, b, c, d, e)](#apidoc.element.eslint.linter.getSource)
- description and source-code
```javascript
getSource = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getSourceCode"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getSourceCode ()](#apidoc.element.eslint.linter.getSourceCode)
- description and source-code
```javascript
getSourceCode = function () {
    return sourceCode;
}
```
- example usage
```shell
...
    this.eslint = eslint;
    this.severity = severity;

    Object.freeze(this);
}

/**
 * Passthrough to eslint.getSourceCode().
 * @returns {SourceCode} The SourceCode object for the code.
 */
getSourceCode() {
    return this.eslint.getSourceCode();
}

/**
...
```

#### <a name="apidoc.element.eslint.linter.getSourceLines"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.eslint.linter.getSourceLines)
- description and source-code
```javascript
getSourceLines = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getTokenAfter"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenAfter)
- description and source-code
```javascript
getTokenAfter = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
 * @param {SourceCode} sourceCode The ESLint source code object
 * @param {ASTNode} node The node to be checked.
 * @returns {boolean} True if the node is parenthesised.
 * @private
 */
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}

/**
...
```

#### <a name="apidoc.element.eslint.linter.getTokenBefore"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenBefore)
- description and source-code
```javascript
getTokenBefore = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
...
 * Determines if a node is surrounded by parentheses.
 * @param {SourceCode} sourceCode The ESLint source code object
 * @param {ASTNode} node The node to be checked.
 * @returns {boolean} True if the node is parenthesised.
 * @private
 */
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}
...
```

#### <a name="apidoc.element.eslint.linter.getTokenByRangeStart"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokenByRangeStart)
- description and source-code
```javascript
getTokenByRangeStart = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getTokens"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokens (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokens)
- description and source-code
```javascript
getTokens = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getTokensAfter"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensAfter)
- description and source-code
```javascript
getTokensAfter = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getTokensBefore"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensBefore)
- description and source-code
```javascript
getTokensBefore = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.getTokensBetween"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.eslint.linter.getTokensBetween)
- description and source-code
```javascript
getTokensBetween = function (a, b, c, d, e) {
    if (sourceCode) {
        return sourceCode[exMethodName](a, b, c, d, e);
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.markVariableAsUsed"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>markVariableAsUsed (name)](#apidoc.element.eslint.linter.markVariableAsUsed)
- description and source-code
```javascript
markVariableAsUsed = function (name) {
    const hasGlobalReturn = currentConfig.parserOptions.ecmaFeatures && currentConfig.parserOptions.ecmaFeatures.globalReturn,
        specialScope = hasGlobalReturn || currentConfig.parserOptions.sourceType === "module";
    let scope = this.getScope(),
        i,
        len;

    // Special Node.js scope means we need to start one level deeper
    if (scope.type === "global" && specialScope) {
        scope = scope.childScopes[0];
    }

    do {
        const variables = scope.variables;

        for (i = 0, len = variables.length; i < len; i++) {
            if (variables[i].name === name) {
                variables[i].eslintUsed = true;
                return true;
            }
        }
    } while ((scope = scope.upper));

    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.report"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>report (ruleId, severity, node, location, message, opts, fix, meta)](#apidoc.element.eslint.linter.report)
- description and source-code
```javascript
report = function (ruleId, severity, node, location, message, opts, fix, meta) {
    if (node) {
        assert.strictEqual(typeof node, "object", "Node must be an object");
    }

    if (typeof location === "string") {
        assert.ok(node, "Node must be provided when reporting error if location is not provided");

        meta = fix;
        fix = opts;
        opts = message;
        message = location;
        location = node.loc.start;
    }

    // Store end location.
    const endLocation = location.end;

    location = location.start || location;

    if (isDisabledByReportingConfig(reportingConfig, ruleId, location)) {
        return;
    }

    if (opts) {
        message = message.replace(/\{\{\s*([^{}]+?)\s*\}\}/g, (fullMatch, term) => {
            if (term in opts) {
                return opts[term];
            }

            // Preserve old behavior: If parameter name not provided, don't replace it.
            return fullMatch;
        });
    }

    const problem = {
        ruleId,
        severity,
        message,
        line: location.line,
        column: location.column + 1,   // switch to 1-base instead of 0-base
        nodeType: node && node.type,
        source: sourceCode.lines[location.line - 1] || ""
    };

    // Define endLine and endColumn if exists.
    if (endLocation) {
        problem.endLine = endLocation.line;
        problem.endColumn = endLocation.column + 1;   // switch to 1-base instead of 0-base
    }

    // ensure there's range and text properties, otherwise it's not a valid fix
    if (fix && Array.isArray(fix.range) && (typeof fix.text === "string")) {

        // If rule uses fix, has metadata, but has no metadata.fixable, we should throw
        if (meta && !meta.fixable) {
            throw new Error("Fixable rules should export a 'meta.fixable' property.");
        }

        problem.fix = fix;
    }

    messages.push(problem);
}
```
- example usage
```shell
...
 * @returns {SourceCode} The SourceCode object for the code.
 */
getSourceCode() {
    return this.eslint.getSourceCode();
}

/**
 * Passthrough to eslint.report() that automatically assigns the rule ID and severity.
 * @param {ASTNode|MessageDescriptor} nodeOrDescriptor The AST node related to the message or a message
 *      descriptor.
 * @param {Object=} location The location of the error.
 * @param {string} message The message to display to the user.
 * @param {Object} opts Optional template data which produces a formatted message
 *     with symbols being replaced by this object's values.
 * @returns {void}
...
```

#### <a name="apidoc.element.eslint.linter.reset"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>reset ()](#apidoc.element.eslint.linter.reset)
- description and source-code
```javascript
reset = function () {
    this.removeAllListeners();
    messages = [];
    currentConfig = null;
    currentScopes = null;
    scopeManager = null;
    traverser = null;
    reportingConfig = [];
    sourceCode = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.linter.verify"></a>[function <span class="apidocSignatureSpan">eslint.linter.</span>verify (textOrSourceCode, config, filenameOrOptions, saveState)](#apidoc.element.eslint.linter.verify)
- description and source-code
```javascript
verify = function (textOrSourceCode, config, filenameOrOptions, saveState) {
    const text = (typeof textOrSourceCode === "string") ? textOrSourceCode : null;
    let ast,
        parseResult,
        shebang,
        allowInlineConfig;

    // evaluate arguments
    if (typeof filenameOrOptions === "object") {
        currentFilename = filenameOrOptions.filename;
        allowInlineConfig = filenameOrOptions.allowInlineConfig;
        saveState = filenameOrOptions.saveState;
    } else {
        currentFilename = filenameOrOptions;
    }

    if (!saveState) {
        this.reset();
    }

    // search and apply "eslint-env *".
    const envInFile = findEslintEnv(text || textOrSourceCode.text);

    config = Object.assign({}, config);

    if (envInFile) {
        if (config.env) {
            config.env = Object.assign({}, config.env, envInFile);
        } else {
            config.env = envInFile;
        }
    }

    // process initial config to make it safe to extend
    config = prepareConfig(config);

    // only do this for text
    if (text !== null) {

        // there's no input, just exit here
        if (text.trim().length === 0) {
            sourceCode = new SourceCode(text, blankScriptAST);
            return messages;
        }

        parseResult = parse(
            stripUnicodeBOM(text).replace(/^#!([^\r\n]+)/, (match, captured) => {
                shebang = captured;
                return '//${captured}';
            }),
            config,
            currentFilename
        );

        // if this result is from a parseForESLint() method, normalize
        if (parseResult && parseResult.ast) {
            ast = parseResult.ast;
        } else {
            ast = parseResult;
            parseResult = null;
        }

        if (ast) {
            sourceCode = new SourceCode(text, ast);
        }

    } else {
        sourceCode = textOrSourceCode;
        ast = sourceCode.ast;
    }

    // if espree failed to parse the file, there's no sense in setting up rules
    if (ast) {

        // parse global comments and modify config
        if (allowInlineConfig !== false) {
            config = modifyConfigsFromComments(currentFilename, ast, config, reportingConfig, messages);
        }

        // ensure that severities are normalized in the config
        ConfigOps.normalize(config);

        // enable appropriate rules
        Object.keys(config.rules).filter(key => getRuleSeverity(config.rules[key]) > 0).forEach(key => {
            let ruleCreator;

            ruleCreator = rules.get(key);

            if (!ruleCreator) {
                const replacementMsg = getRuleReplacementMessage(key);

                if (replacementMsg) {
                    ruleCreator = createStubRule(replacementMsg);
                } else {
                    ruleCreator = createStubRule('Definition for rule '${key}' was not found');
                }
                rules.define(key, ruleCreator);
            }

            const severity = getRuleSeverity(config.rules[key]);
            const options = getRuleOptions(config.rules[key]);

            try {
                const ruleContext = new RuleContext(
                    key, api, severity, options,
                    config.settings, config.parserOptions, config.parser,
                    ruleCreator.meta,
                    (parseResult && parseResult.services ? parseResult.services : {})
                );

                const rule = ruleCreator.create ? ruleCreator.create(ruleContext)
                    : ruleCreator(ruleContext);

                // add all the selectors from the rule as listeners
                Object.keys(rule).forEach(selector => {
                    api.on(selector, timing.enabled
                        ? timing.time(key, rule[selector])
                        : rule[selector]
                    );
                });
            } catch (ex) {
                ex.message = 'Error while loading rule '${key}': ${ex.message}';
                throw ex;
            }
        });

        // save config so rules can access as necess ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.logging"></a>[module eslint.logging](#apidoc.module.eslint.logging)

#### <a name="apidoc.element.eslint.logging.error"></a>[function <span class="apidocSignatureSpan">eslint.logging.</span>error ()](#apidoc.element.eslint.logging.error)
- description and source-code
```javascript
error() {
    console.error.apply(console, Array.prototype.slice.call(arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.logging.info"></a>[function <span class="apidocSignatureSpan">eslint.logging.</span>info ()](#apidoc.element.eslint.logging.info)
- description and source-code
```javascript
info() {
    console.log.apply(console, Array.prototype.slice.call(arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.options"></a>[module eslint.options](#apidoc.module.eslint.options)

#### <a name="apidoc.element.eslint.options.generateHelp"></a>[function <span class="apidocSignatureSpan">eslint.options.</span>generateHelp (arg$)](#apidoc.element.eslint.options.generateHelp)
- description and source-code
```javascript
generateHelp = function (arg$){
  var ref$, showHidden, interpolate, maxWidth, output, out, data, optionCount, totalPreLen, preLens, i$, len$, item, that, pre,
descParts, desc, preLen, sortedPreLens, maxPreLen, preLenMean, x, padAmount, descSepLen, fullWrapCount, partialWrapCount, descLen
, totalLen, initialSpace, wrapAllFull, i, wrap;
  ref$ = arg$ != null
    ? arg$
    : {}, showHidden = ref$.showHidden, interpolate = ref$.interpolate;
  maxWidth = stdout != null && stdout.isTTY ? stdout.columns - 1 : null;
  output = [];
  out = function(it){
    return output.push(it != null ? it : '');
  };
  if (prepend) {
    out(interpolate ? interp(prepend, interpolate) : prepend);
    out();
  }
  data = [];
  optionCount = 0;
  totalPreLen = 0;
  preLens = [];
  for (i$ = 0, len$ = (ref$ = options).length; i$ < len$; ++i$) {
    item = ref$[i$];
    if (showHidden || !item.hidden) {
      if (that = item.heading) {
        data.push({
          type: 'heading',
          value: that
        });
      } else {
        pre = getPreText(item, helpStyle, maxWidth);
        descParts = [];
        if ((that = item.description) != null) {
          descParts.push(that);
        }
        if (that = item['enum']) {
          descParts.push("either: " + naturalJoin(that));
        }
        if (item['default'] && !item.negateName) {
          descParts.push("default: " + item['default']);
        }
        desc = descParts.join(' - ');
        data.push({
          type: 'option',
          pre: pre,
          desc: desc,
          descLen: desc.length
        });
        preLen = pre.length;
        optionCount++;
        totalPreLen += preLen;
        preLens.push(preLen);
      }
    }
  }
  sortedPreLens = sort(preLens);
  maxPreLen = sortedPreLens[sortedPreLens.length - 1];
  preLenMean = initialIndent + totalPreLen / optionCount;
  x = optionCount > 2 ? min(preLenMean * maxPadFactor, maxPreLen) : maxPreLen;
  for (i$ = sortedPreLens.length - 1; i$ >= 0; --i$) {
    preLen = sortedPreLens[i$];
    if (preLen <= x) {
      padAmount = preLen;
      break;
    }
  }
  descSepLen = descriptionSeparator.length;
  if (maxWidth != null) {
    fullWrapCount = 0;
    partialWrapCount = 0;
    for (i$ = 0, len$ = data.length; i$ < len$; ++i$) {
      item = data[i$];
      if (item.type === 'option') {
        pre = item.pre, desc = item.desc, descLen = item.descLen;
        if (descLen === 0) {
          item.wrap = 'none';
        } else {
          preLen = max(padAmount, pre.length) + initialIndent + descSepLen;
          totalLen = preLen + descLen;
          if (totalLen > maxWidth) {
            if (descLen / 2.5 > maxWidth - preLen) {
              fullWrapCount++;
              item.wrap = 'full';
            } else {
              partialWrapCount++;
              item.wrap = 'partial';
            }
          } else {
            item.wrap = 'none';
          }
        }
      }
    }
  }
  initialSpace = repeatString$(' ', initialIndent);
  wrapAllFull = optionCount > 1 && fullWrapCount + partialWrapCount * 0.5 > optionCount * 0.5;
  for (i$ = 0, len$ = data.length; i$ < len$; ++i$) {
    i = i$;
    item = data[i$];
    if (item.type === 'heading') {
      if (i !== 0) {
        out();
      }
      out(item.value + ":");
    } else {
      pre = item.pre, desc = item.desc, descLen = item.descLen, wrap = item.wrap;
      if (maxWidth != null) {
        if (wrapAllFull || wrap === 'full') {
          wrap = wordwrap(initialIndent + secondaryIndent, maxWidth);
          out(initialSpace + "" + pre + "\n" + wrap(desc));
          continue;
        } else if (wrap === 'partial') {
          wrap = wordwrap(initialIndent + descSepLen + max(padAmount, pre.length), maxWidth);
          out(initialSpace + "" + pad(pre, padAmount) + descriptionSeparator + wrap(desc).replace(/^\s+/, ''));
          continue;
        }
      }
      if (descLen === 0) {
        out(initialSpace + "" + pre);
      } else {
        out(initialSpace + "" + pad(pre, padAmount) + descriptionSeparator + desc);
      }
    }
  }
  if (append) {
    out();
    out(interpola ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.options.generateHelpForOption"></a>[function <span class="apidocSignatureSpan">eslint.options.</span>generateHelpForOption (optionName)](#apidoc.element.eslint.options.generateHelpForOption)
- description and source-code
```javascript
generateHelpForOption = function (optionName){
  var maxWidth, wrap, option, e, pre, defaultString, restPositionalString, description, fullDescription, that, preDescription, descriptionString
, exampleString, examples, seperator;
  maxWidth = stdout != null && stdout.isTTY ? stdout.columns - 1 : null;
  wrap = maxWidth ? wordwrap(maxWidth) : id;
  try {
    option = getOption(dasherize(optionName));
  } catch (e$) {
    e = e$;
    return e.message;
  }
  pre = getPreText(option, helpStyle);
  defaultString = option['default'] && !option.negateName ? "\ndefault: " + option['default'] : '';
  restPositionalString = option.restPositional ? 'Everything after this option is considered a positional argument, even if it looks
 like an option.' : '';
  description = option.longDescription || option.description && sentencize(option.description);
  fullDescription = description && restPositionalString
    ? description + " " + restPositionalString
    : (that = description || restPositionalString) ? that : '';
  preDescription = 'description:';
  descriptionString = !fullDescription
    ? ''
    : maxWidth && fullDescription.length - 1 - preDescription.length > maxWidth
      ? "\n" + preDescription + "\n" + wrap(fullDescription)
      : "\n" + preDescription + " " + fullDescription;
  exampleString = (that = option.example) ? (examples = [].concat(that), examples.length > 1
    ? "\nexamples:\n" + unlines(examples)
    : "\nexample: " + examples[0]) : '';
  seperator = defaultString || descriptionString || exampleString ? "\n" + repeatString$('=', pre.length) : '';
  return pre + "" + seperator + defaultString + descriptionString + exampleString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.options.parse"></a>[function <span class="apidocSignatureSpan">eslint.options.</span>parse (input, arg$)](#apidoc.element.eslint.options.parse)
- description and source-code
```javascript
parse = function (input, arg$){
  var slice, obj, positional, restPositional, overrideRequired, prop, setValue, setDefaults, checkRequired, mutuallyExclusiveError
, checkMutuallyExclusive, checkDependency, checkDependencies, checkProp, args, key, value, option, ref$, i$, len$, arg, that, result
, short, argName, usingAssign, val, flags, len, j$, len1$, i, flag, opt, name, valPrime, negated, noedName;
  slice = (arg$ != null
    ? arg$
    : {}).slice;
  obj = {};
  positional = [];
  restPositional = false;
  overrideRequired = false;
  prop = null;
  setValue = function(name, value){
    var opt, val, cra, e, currentType;
    opt = getOption(name);
    if (opt.boolean) {
      val = value;
    } else {
      try {
        cra = opt.concatRepeatedArrays;
        if (cra != null && cra[0] && cra[1].oneValuePerFlag && opt.parsedType.length === 1 && opt.parsedType[0].structure === 'array
') {
          val = [parseLevn(opt.parsedType[0].of, value)];
        } else {
          val = parseLevn(opt.parsedType, value);
        }
      } catch (e$) {
        e = e$;
        throw new Error("Invalid value for option '" + name + "' - expected type " + opt.type + ", received value: " + value + ".");
      }
      if (opt['enum'] && !any(function(it){
        return deepIs(it, val);
      }, opt.parsedPossibilities)) {
        throw new Error("Option " + name + ": '" + val + "' not one of " + naturalJoin(opt['enum']) + ".");
      }
    }
    currentType = toString$.call(obj[name]).slice(8, -1);
    if (obj[name] != null) {
      if (opt.concatRepeatedArrays != null && opt.concatRepeatedArrays[0] && currentType === 'Array') {
        obj[name] = obj[name].concat(val);
      } else if (opt.mergeRepeatedObjects && currentType === 'Object') {
        import$(obj[name], val);
      } else {
        obj[name] = val;
      }
    } else {
      obj[name] = val;
    }
    if (opt.restPositional) {
      restPositional = true;
    }
    if (opt.overrideRequired) {
      overrideRequired = true;
    }
  };
  setDefaults = function(){
    var name, ref$, value;
    for (name in ref$ = defaults) {
      value = ref$[name];
      if (obj[name] == null) {
        obj[name] = value;
      }
    }
  };
  checkRequired = function(){
    var i$, ref$, len$, name;
    if (overrideRequired) {
      return;
    }
    for (i$ = 0, len$ = (ref$ = required).length; i$ < len$; ++i$) {
      name = ref$[i$];
      if (!obj[name]) {
        throw new Error("Option " + nameToRaw(name) + " is required.");
      }
    }
  };
  mutuallyExclusiveError = function(first, second){
    throw new Error("The options " + nameToRaw(first) + " and " + nameToRaw(second) + " are mutually exclusive - you cannot use
them at the same time.");
  };
  checkMutuallyExclusive = function(){
    var rules, i$, len$, rule, present, j$, len1$, element, k$, len2$, opt;
    rules = libOptions.mutuallyExclusive;
    if (!rules) {
      return;
    }
    for (i$ = 0, len$ = rules.length; i$ < len$; ++i$) {
      rule = rules[i$];
      present = null;
      for (j$ = 0, len1$ = rule.length; j$ < len1$; ++j$) {
        element = rule[j$];
        if (toString$.call(element).slice(8, -1) === 'Array') {
          for (k$ = 0, len2$ = element.length; k$ < len2$; ++k$) {
            opt = element[k$];
            if (opt in obj) {
              if (present != null) {
                mutuallyExclusiveError(present, opt);
              } else {
                present = opt;
                break;
              }
            }
          }
        } else {
          if (element in obj) {
            if (present != null) {
              mutuallyExclusiveError(present, element);
            } else {
              present = element;
            }
          }
        }
      }
    }
  };
  checkDependency = function(option){
    var dependsOn, type, targetOptionNames, i$, len$, targetOptionName, targetOption;
    dependsOn = option.dependsOn;
    if (!dependsOn || option.dependenciesMet) {
      return true;
    }
    type = dependsOn[0], targetOptionNames = slice$.call(dependsOn, 1);
    for (i$ = 0, len$ = ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.options.parseArgv"></a>[function <span class="apidocSignatureSpan">eslint.options.</span>parseArgv (it)](#apidoc.element.eslint.options.parseArgv)
- description and source-code
```javascript
parseArgv = function (it){
  return parse(it, {
    slice: 2
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.rule_context"></a>[module eslint.rule_context](#apidoc.module.eslint.rule_context)

#### <a name="apidoc.element.eslint.rule_context.rule_context"></a>[function <span class="apidocSignatureSpan">eslint.</span>rule_context (ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices)](#apidoc.element.eslint.rule_context.rule_context)
- description and source-code
```javascript
class RuleContext {

<span class="apidocCodeCommentSpan">    /**
     * @param {string} ruleId The ID of the rule using this object.
     * @param {eslint} eslint The eslint object.
     * @param {number} severity The configured severity level of the rule.
     * @param {Array} options The configuration information to be added to the rule.
     * @param {Object} settings The configuration settings passed from the config file.
     * @param {Object} parserOptions The parserOptions settings passed from the config file.
     * @param {Object} parserPath The parser setting passed from the config file.
     * @param {Object} meta The metadata of the rule
     * @param {Object} parserServices The parser services for the rule.
     */
</span>    constructor(ruleId, eslint, severity, options, settings, parserOptions, parserPath, meta, parserServices) {

        // public.
        this.id = ruleId;
        this.options = options;
        this.settings = settings;
        this.parserOptions = parserOptions;
        this.parserPath = parserPath;
        this.meta = meta;

        // create a separate copy and freeze it (it's not nice to freeze other people's objects)
        this.parserServices = Object.freeze(Object.assign({}, parserServices));

        // private.
        this.eslint = eslint;
        this.severity = severity;

        Object.freeze(this);
    }

    /**
     * Passthrough to eslint.getSourceCode().
     * @returns {SourceCode} The SourceCode object for the code.
     */
    getSourceCode() {
        return this.eslint.getSourceCode();
    }

    /**
     * Passthrough to eslint.report() that automatically assigns the rule ID and severity.
     * @param {ASTNode|MessageDescriptor} nodeOrDescriptor The AST node related to the message or a message
     *      descriptor.
     * @param {Object=} location The location of the error.
     * @param {string} message The message to display to the user.
     * @param {Object} opts Optional template data which produces a formatted message
     *     with symbols being replaced by this object's values.
     * @returns {void}
     */
    report(nodeOrDescriptor, location, message, opts) {

        // check to see if it's a new style call
        if (arguments.length === 1) {
            const descriptor = nodeOrDescriptor;
            let fix = null;

            // if there's a fix specified, get it
            if (typeof descriptor.fix === "function") {
                fix = descriptor.fix(ruleFixer);
            }

            this.eslint.report(
                this.id,
                this.severity,
                descriptor.node,
                descriptor.loc || descriptor.node.loc.start,
                descriptor.message,
                descriptor.data,
                fix,
                this.meta
            );

            return;
        }

        // old style call
        this.eslint.report(
            this.id,
            this.severity,
            nodeOrDescriptor,
            location,
            message,
            opts,
            this.meta
        );
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.rule_context.prototype"></a>[module eslint.rule_context.prototype](#apidoc.module.eslint.rule_context.prototype)

#### <a name="apidoc.element.eslint.rule_context.prototype.getAllComments"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getAllComments (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getAllComments)
- description and source-code
```javascript
getAllComments = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getAncestors"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getAncestors (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getAncestors)
- description and source-code
```javascript
getAncestors = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getComments"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getComments (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getComments)
- description and source-code
```javascript
getComments = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
       return true;
   }

   // Checks '@this' in its leading comments for callbacks,
   // because callbacks don't have its JSDoc comment.
   // e.g.
   //     sinon.test(/* @this sinon.Sandbox */function() { this.spy(); });
   return sourceCode.getComments(node).leading.some(comment => thisTagPattern.test(comment.value));
}

/**
* Determines if a node is surrounded by parentheses.
* @param {SourceCode} sourceCode The ESLint source code object
* @param {ASTNode} node The node to be checked.
* @returns {boolean} True if the node is parenthesised.
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getDeclaredVariables"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getDeclaredVariables (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getDeclaredVariables)
- description and source-code
```javascript
getDeclaredVariables = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getFilename"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFilename (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFilename)
- description and source-code
```javascript
getFilename = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getFirstToken"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFirstToken (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFirstToken)
- description and source-code
```javascript
getFirstToken = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
* @param {ASTNode} node - The function node to get.
* @param {SourceCode} sourceCode - The source code object to get tokens.
* @returns {Token} '(' token.
*/
function getOpeningParenOfParams(node, sourceCode) {
   return node.id
       ? sourceCode.getTokenAfter(node.id, isOpeningParenToken)
       : sourceCode.getFirstToken(node, isOpeningParenToken);
}

/**
* Creates a version of the LINEBREAK_MATCHER regex with the global flag.
* Global regexes are mutable, so this needs to be a function instead of a constant.
* @returns {RegExp} A global regular expression that matches line terminators
*/
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getFirstTokens"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getFirstTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getFirstTokens)
- description and source-code
```javascript
getFirstTokens = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getJSDocComment"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getJSDocComment (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getJSDocComment)
- description and source-code
```javascript
getJSDocComment = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
/**
 * Checks whether or not a node has a '@this' tag in its comments.
 * @param {ASTNode} node - A node to check.
 * @param {SourceCode} sourceCode - A SourceCode instance to get comments.
 * @returns {boolean} Whether or not the node has a '@this' tag in its comments.
 */
function hasJSDocThisTag(node, sourceCode) {
const jsdocComment = sourceCode.getJSDocComment(node);

if (jsdocComment && thisTagPattern.test(jsdocComment.value)) {
    return true;
}

// Checks '@this' in its leading comments for callbacks,
// because callbacks don't have its JSDoc comment.
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getLastToken"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getLastToken (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getLastToken)
- description and source-code
```javascript
getLastToken = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
    * surrounding the node.
    * @param {SourceCode} sourceCode The source code object
    * @param {ASTNode} node An expression node
    * @returns {string} The text representing the node, with all surrounding parentheses included
    */
    getParenthesisedText(sourceCode, node) {
let leftToken = sourceCode.getFirstToken(node);
let rightToken = sourceCode.getLastToken(node);

while (
    sourceCode.getTokenBefore(leftToken) &&
    sourceCode.getTokenBefore(leftToken).type === "Punctuator" &&
    sourceCode.getTokenBefore(leftToken).value === "(" &&
    sourceCode.getTokenAfter(rightToken) &&
    sourceCode.getTokenAfter(rightToken).type === "Punctuator" &&
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getLastTokens"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getLastTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getLastTokens)
- description and source-code
```javascript
getLastTokens = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getNodeByRangeIndex"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getNodeByRangeIndex (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getNodeByRangeIndex)
- description and source-code
```javascript
getNodeByRangeIndex = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getScope"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getScope (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getScope)
- description and source-code
```javascript
getScope = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getSource"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getSource (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getSource)
- description and source-code
```javascript
getSource = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getSourceLines"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getSourceLines (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getSourceLines)
- description and source-code
```javascript
getSourceLines = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokenAfter"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenAfter (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenAfter)
- description and source-code
```javascript
getTokenAfter = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
 * @param {SourceCode} sourceCode The ESLint source code object
 * @param {ASTNode} node The node to be checked.
 * @returns {boolean} True if the node is parenthesised.
 * @private
 */
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}

/**
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokenBefore"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenBefore (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenBefore)
- description and source-code
```javascript
getTokenBefore = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
...
 * Determines if a node is surrounded by parentheses.
 * @param {SourceCode} sourceCode The ESLint source code object
 * @param {ASTNode} node The node to be checked.
 * @returns {boolean} True if the node is parenthesised.
 * @private
 */
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}
...
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokenByRangeStart"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokenByRangeStart (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokenByRangeStart)
- description and source-code
```javascript
getTokenByRangeStart = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokens"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokens (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokens)
- description and source-code
```javascript
getTokens = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokensAfter"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensAfter (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensAfter)
- description and source-code
```javascript
getTokensAfter = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokensBefore"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensBefore (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensBefore)
- description and source-code
```javascript
getTokensBefore = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.getTokensBetween"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>getTokensBetween (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.getTokensBetween)
- description and source-code
```javascript
getTokensBetween = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rule_context.prototype.markVariableAsUsed"></a>[function <span class="apidocSignatureSpan">eslint.rule_context.prototype.</span>markVariableAsUsed (a, b, c, d, e)](#apidoc.element.eslint.rule_context.prototype.markVariableAsUsed)
- description and source-code
```javascript
markVariableAsUsed = function (a, b, c, d, e) {
    return this.eslint[name](a, b, c, d, e);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.rules"></a>[module eslint.rules](#apidoc.module.eslint.rules)

#### <a name="apidoc.element.eslint.rules.define"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>define (ruleId, ruleModule)](#apidoc.element.eslint.rules.define)
- description and source-code
```javascript
function define(ruleId, ruleModule) {
    rules[ruleId] = ruleModule;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rules.get"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>get (ruleId)](#apidoc.element.eslint.rules.get)
- description and source-code
```javascript
function getHandler(ruleId) {
    if (typeof rules[ruleId] === "string") {
        return require(rules[ruleId]);
    }
    return rules[ruleId];

}
```
- example usage
```shell
...
    rules = require("../lib/rules");

//------------------------------------------------------------------------------
// Helpers
//------------------------------------------------------------------------------

const enabledRules = Object.keys(load()).reduce((result, ruleId) => {
    if (!rules.get(ruleId).meta.deprecated) {
        result[ruleId] = "error";
    }
    return result;
}, {});

//------------------------------------------------------------------------------
// Public Interface
...
```

#### <a name="apidoc.element.eslint.rules.getAllLoadedRules"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>getAllLoadedRules ()](#apidoc.element.eslint.rules.getAllLoadedRules)
- description and source-code
```javascript
function getAllLoadedRules() {
    const allRules = new Map();

    Object.keys(rules).forEach(name => {
        const rule = getHandler(name);

        allRules.set(name, rule);
    });
    return allRules;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rules.importPlugin"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>importPlugin (plugin, pluginName)](#apidoc.element.eslint.rules.importPlugin)
- description and source-code
```javascript
function importPlugin(plugin, pluginName) {
    if (plugin.rules) {
        Object.keys(plugin.rules).forEach(ruleId => {
            const qualifiedRuleId = '${pluginName}/${ruleId}',
                rule = plugin.rules[ruleId];

            define(qualifiedRuleId, rule);
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rules.load"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>load (rulesDir, cwd)](#apidoc.element.eslint.rules.load)
- description and source-code
```javascript
function load(rulesDir, cwd) {
    const newRules = loadRules(rulesDir, cwd);

    Object.keys(newRules).forEach(ruleId => {
        define(ruleId, newRules[ruleId]);
    });
}
```
- example usage
```shell
...
            config = configToLoad;

            if (config.extends) {
                config = ConfigFile.applyExtends(config, filePath);
            }
        } else {
            filePath = configToLoad;
            config = ConfigFile.load(filePath);
        }

    }

    return config;
}
...
```

#### <a name="apidoc.element.eslint.rules.testClear"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>testClear ()](#apidoc.element.eslint.rules.testClear)
- description and source-code
```javascript
function testClear() {
    rules = Object.create(null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint.rules.testReset"></a>[function <span class="apidocSignatureSpan">eslint.rules.</span>testReset ()](#apidoc.element.eslint.rules.testReset)
- description and source-code
```javascript
testReset() {
    testClear();
    load();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint.timing"></a>[module eslint.timing](#apidoc.module.eslint.timing)

#### <a name="apidoc.element.eslint.timing.time"></a>[function <span class="apidocSignatureSpan">eslint.timing.</span>time (key, fn)](#apidoc.element.eslint.timing.time)
- description and source-code
```javascript
function time(key, fn) {
    if (typeof data[key] === "undefined") {
        data[key] = 0;
    }

    return function() {
        let t = process.hrtime();

        fn.apply(null, Array.prototype.slice.call(arguments));
        t = process.hrtime(t);
        data[key] += t[0] * 1e3 + t[1] / 1e6;
    };
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
