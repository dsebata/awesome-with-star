# Information comes from [burningtree/awesome-json](https://github.com/burningtree/awesome-json)
# Awesome JSON [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome JSON libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

* [Awesome JSON](#awesome-json)
  * [Applications](#applications)
  * [Binary Serialization](#binary-serialization)
  * [Browser Extensions](#browser-extensions)
  * [Command-line tools](#command-line-tools)
  * [Databases](#databases)
  * [Datasets](#datasets)
  * [Data modeling](#data-modeling)
  * [Data generation](#data-generation)
  * [Differencing](#differencing)
  * [Format Extensions](#format-extensions)
  * [Frontend components](#frontend-components)
  * [Libraries](#libraries)
  * [Linters](#linters)
  * [Online tools](#online-tools)
  * [Schema Specifications](#schema-specifications)
  * [Services](#services)
  * [Supersets](#supersets)
  * [Related formats](#related-formats)
  * [Resources](#resources)
  * [Templates](#templates)
  * [Testing](#testing)
  * [Text Editor Plugins](#text-editor-plugins)
  * [Transformations](#transformations)
  * [Tutorials](#tutorials)
  * [Queries](#queries)
  * [JSON Schema Frontend components](#json-schema-frontend-components)
  * [JSON Schema Tools](#json-schema-tools)
  * [JSON Schema Resources](#json-schema-resources)
  * [JSON Schema Validators](#json-schema-validators)
  * [Contribute](#contribute)

## Applications
**OS X**
* [Visual JSON](https://itunes.apple.com/app/id488709442) ([github](https://github.com/youknowone/VisualJSON)) - simple JSON pretty-viewer for Mac OS X. :star:276
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - convert a object to a class of one of the currently supported languages. :star:4051

## Binary Serialization
* [BSON](http://bsonspec.org/) - Binary JSON.
* [MessagePack](https://msgpack.org/) - An extremely efficient object serialization library.
* [UBJSON](http://ubjson.org/) - The universally compatible format specification for binary JSON.
* [CBOR](https://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation.
* [PSON](https://github.com/dcodeIO/PSON) - Protocol JSON, super efficient binary serialization format. :star:406

## Browser Extensions
**Chrome**
* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github](https://github.com/callumlocke/json-formatter)) - Makes JSON easy to read. Open source. :star:1983
* [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github](https://github.com/tulios/json-viewer)) - It is a Chrome extension for printing JSON and JSONP. :star:1539
* [JSON Browser](https://chrome.google.com/webstore/detail/json-browser/hngfgkmimoikmpohakflgadcajkfnoba) ([github](https://github.com/platy/json-browser/)) - Browse a JSON web with the help of JSON schemas. :star:11
* [JSON Finder](https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github](https://github.com/rapee/jsonfinder)) - Browse like you do it in Finder. :star:34
* [JSON Viewer Awesome](https://chrome.google.com/webstore/detail/json-viewer-awesome/iemadiahhbebdklepanmkjenfdebfpfe/related?hl=en) - An open source Chrome extension for browsing JSON with syntax highlighting and folding, or as a visual graph.

**Firefox**
* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github](https://github.com/bhollis/jsonview)) - View JSON documents in the browser. :star:800

**Safari**
* [JSONAce](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonace-56Q494QF3L) ([github](https://github.com/acrogenesis/JSONAce)) - Formats & syntax highlights JSON viewed inside of the web browser using the ACE editor. :star:71
* [JSONView](https://safari-extensions.apple.com/details/?id=com.acrogenesis.jsonview-56Q494QF3L) ([github](https://github.com/acrogenesis/jsonview-safari)) - A port of the JSONView Firefox extension that formats and syntax highlights JSON viewed inside of the browser :star:290

## Command-line tools
* [fx](https://github.com/antonmedv/fx) - A interactive terminal tool. :star:8152
* [jsoncat](https://github.com/pantuza/jsoncat) - Pretty-print Json in terminal with colors and adjusting tabs size. :star:20
* [jq](http://stedolan.github.io/jq/) - A lightweight and flexible command-line JSON processor.
* [json](http://trentm.com/json/) - A "json" command for massaging JSON on your Unix command line.
* [jshon](http://kmkeen.com/jshon/) - A parser designed for maximum convenience within the shell.
* [jarg](http://jdp.github.io/jarg/) - Shorthand JSON and form encoding syntax in the shell.
* [jsawk](https://github.com/micha/jsawk) - Like awk, but for JSON. :star:1285
* [gron](https://github.com/tomnomnom/gron) - Convert a JSON file into discrete assignments that are greppable. :star:5651
* [jid](https://github.com/simeji/jid) - Incremental Digger. Drill down JSON interactively by using filtering queries like jq. :star:5278
* [jiq](https://github.com/fiatjaf/jiq) - It's `jid` with `jq`. You can drill down interactively by using `jq` filtering queries. :star:296
* [jv](https://github.com/maxzender/jv) - jv (for jsonviewer) helps you view your JSON. :star:98
* [jl](https://github.com/chrisdone/jl) - Functional sed for JSON. :star:386

## Databases
* [MongoDB](https://www.mongodb.com/) - an open-source document database, and the leading NoSQL database.
* [RethinkDB](https://rethinkdb.com/) - An open-source distributed document database with a pleasant and powerful query language.
* [EJDB](https://github.com/Softmotions/ejdb) - Embedded JSON Database engine published under MIT license. (C) :star:996
* [lowdb](https://github.com/typicode/lowdb) - Flat file database built on lodash API. (Javascript) :star:11152
* [Lawnchair](https://github.com/brianleroux/lawnchair) - A lightweight clientside document store. (Javascript) :star:2155
* [JSON ODM](https://github.com/konsultaner/jsonOdm) - Object document mapper for JavaScript to use on the server or in the browser. (Javascript) :star:70
* [JSON Server](https://github.com/typicode/json-server) - Get a full fake REST API with zero coding in less than 30 seconds. :star:41969
* [Kinto](https://github.com/Kinto/kinto) - A lightweight JSON storage service with synchronisation and sharing abilities. :star:3790
* [CouchDB](http://couchdb.apache.org/) - Seamless multi-master sync, that scales from Big Data to Mobile, with an Intuitive HTTP/JSON API and designed for Reliability.
* [RxDB](https://github.com/pubkey/rxdb) - Event-driven JSON-Database with JSON-Schema, mango-Query and CouchDB-sync. (Javascript) :star:9478
* [JSONlite](https://github.com/nodesocket/jsonlite) - A simple, self-contained, serverless, zero-configuration, json document store. (Bash) :star:816

## Datasets
* [country.io](http://country.io/data/) - Various country related datasets, as JSON inc currency, country codes, names and more
* [countries](https://github.com/mledoze/countries) - World countries. :star:4465
* [vat-rates](http://jsonvat.com/) - VAT rates for all EU countries.
* [MTG JSON](https://mtgjson.com/) - Up to date Magic the Gathering card data.
* [Heartstone JSON](https://hearthstonejson.com/) - Up to date Hearthstone card data.
* [getCountries()](http://peric.github.io/GetCountries/) - Generator for custom Countries data.

## Data modeling
* [JSONModel](https://github.com/jsonmodel/jsonmodel ) - Magical Data Modelling Framework. (Objective-C) :star:6754

## Data generation
* [jsonymize](https://github.com/cameronhunter/jsonymize) - Reads data from standard input, anonymizes, then writes to standard output. :star:10
* [dyson](https://github.com/webpro/dyson) - Server for dynamic, fake JSON. (node.js) :star:764

## Differencing
* [JSONPatch](http://jsonpatch.com/) - A format for describing changes to a document.
* [JSON-Patch](https://github.com/Starcounter-Jack/JSON-Patch) - Lean and mean Javascript implementation of the JSON-Patch standard (RFC 6902). (Javascript) :star:1032
* [jiff](https://github.com/cujojs/jiff) - JSON Patch and diff based on rfc6902. (Javascript) :star:363
* [json-patch-php](https://github.com/mikemccabe/json-patch-php) - implementation of JSON-patch (IETF RFC 6902) (PHP) :star:92
* [dffptch](https://github.com/paldepind/dffptch) - A micro library for diffing and patching using a compact diff format. (Javascript) :star:162
* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - Diff & patch for JavaScript objects. (Javascript) :star:2925

## Editors
* [JSONEdit](http://mb21.github.io/JSONedit/) - User friendly, visual editor built as an AngularJS directive.

## Format Extensions
* [GeoJSON](https://geojson.org/) - A geospatial data interchange format.
* [JSON-LD](https://json-ld.org/) - A lightweight Linked Data format.
* [JSON-RPC](https://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSONP](https://en.wikipedia.org/wiki/JSONP) - Safer cross-domain Ajax with JSON-P/JSONP.
* [JsonML](http://www.jsonml.org/) - A compact format for transporting XML-based markup as JSON which allows it to be losslessly converted back to its original form.
* [JSON5](https://json5.org/) - a extension that aims to make it easier for humans to write and maintain by hand.
* [JSON6](https://github.com/d3x0r/json6) - JSON for Humans (ES6). :star:123
* [JSON Resume](https://jsonresume.org/) - The open source initiative to create standard for resumes.
* [JSON Web Tokens](https://jwt.io/) - A compact URL-safe means of representing claims to be transferred between two parties.
* [JSON API](https://jsonapi.org/) - A standard for building APIs.
* [Collection+JSON](http://amundsen.com/media-types/collection/) - A read/write hypermedia-type designed to support management and querying of simple collections.
* [hal-json](http://stateless.co/hal_specification.html) - A set of conventions for expressing hyperlinks in either JSON or XML.
* [JSON Activity Streams](http://activitystrea.ms/) - A format for syndicating social activities around the web.
* [JSON-stat](https://github.com/jsonstat/jsonstat) - Simple lightweight format for data dissemination. :star:18
* [/contribute.json](https://www.contributejson.org/) - Making open source contribution information easier to access, across projects.
* [JSON Table Schema](https://frictionlessdata.io/docs/json-table-schema/) - a simple schema for tabular data
* [NDJSON](http://ndjson.org/) (Newline delimited JSON) - a standard for delimiting JSON in stream protocols.
* [survey.js](http://surveyjs.org/) - JSON based survey library.
* [JSON Meta Application Protocol (JMAP)](https://jmap.io/) - A protocol for synchronising JSON-based data objects efficiently, with support for push and out-of-band binary data upload/download.
* [J<sub>ack</sub>SON: JSON secret keeper](https://github.com/r0hi7/jackson) - JSONic way of storing secrets in config file. :star:14

## Frontend components
* [JSON editor jQuery plugin](https://github.com/DavidDurman/FlexiJsonEditor) - component for you web apps/pages. (jQuery) :star:516
* [jqTree](http://mbraak.github.io/jqTree/) - Widget for displaying a tree structure in html. (jQuery)
* [jsTree](https://www.jstree.com/docs/json/) - jquery plugin, that provides interactive trees. (jQuery)
* [Dynatable.js](https://www.dynatable.com/) - A funner, semantic, HTML5+JSON, interactive table plugin. (jQuery)
* [JSON Formatter](https://github.com/mohsen1/json-formatter) - Angular directive for collapsible JSON in HTML. (AngularJS) :star:362
* [react-jsonschema-form](https://mozilla-services.github.io/react-jsonschema-form/) - A React component for building Web forms from JSON Schema. (React)

## Libraries
**C**
* [Jansson](http://www.digip.org/jansson/) - A C library for encoding, decoding and manipulating data.
* [jsmn](https://zserge.com/jsmn.html) - A minimalistic parser in C. It can be easily integrated into the resource-limited projects or embedded systems.

**C++**
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) - An efficient library for embedded systems. :star:3884
* [JSON++](https://github.com/tunnuz/json) - A self contained Flex/Bison parser for C++11. :star:38
* [json11](https://github.com/dropbox/json11) - A tiny library for C++11. :star:1841
* [RapidJSON](https://github.com/Tencent/rapidjson) - A fast JSON parser/generator for C++ with both SAX/DOM style API :star:8081

**Clojure**
* [data.json](https://github.com/clojure/data.json) - parser/generator to/from Clojure data structures. :star:352

**Fortran**
* [JSON-Fortran](https://github.com/jacobwilliams/json-fortran) - A Fortran library for writing, reading, and manipulating JSON files and data structures. :star:171

**Haskell**
* [aeson-qq](https://github.com/sol/aeson-qq) - JSON quasiquoter for Haskell. :star:57
* [json-schema](http://hackage.haskell.org/package/json-schema) - JSON Schema library for Haskell
* [hjsonschema](http://hackage.haskell.org/package/hjsonschema) - JSON Schema Draft 4 library for Haskell

**Java**
* [JSON-java](https://github.com/stleary/JSON-java) - A reference implementation. :star:3340
* [Fast JSON Processor](https://github.com/alibaba/fastjson) :star:18813
* [Gson](https://github.com/google/gson) - A Java library to convert JSON to Java objects and vice-versa. :star:16221
* [Jackson](https://github.com/FasterXML/jackson) - A multi-purpose Java library for processing JSON data format. :star:4902
* [moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java. :star:5365

**Javascript**
* [JSON-js](https://github.com/douglascrockford/JSON-js) - JSON in JavaScript. :star:7957
* [JSON 3](https://bestiejs.github.io/json3/) - A modern implementation.
* [oboe.js](http://oboejs.com/) - A streaming approach, speeds up web applications by providing parsed objects before the response completes.

**Objective-C**
* [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C library. :star:6218
* [SBJson](https://stig.github.io/json-framework/) - Parse one or more chunks of data.

**Perl**
* [JSON::Tiny](https://github.com/daoswald/JSON-Tiny) - Perl module for encoding and decoding JSON in a minimalistic way. :star:11

**PL/SQL**
* [PL/JSON](https://github.com/pljson/pljson) - A generic JSON object written in PL/SQL. :star:276

**PHP**
* [Webmozart JSON](https://github.com/webmozart/json) - A robust decoder/encoder with support for schema validation. :star:341

**Python**
* [simplejson](https://github.com/simplejson/simplejson) - A simple, fast, extensible encoder/decoder :star:1165
* [jsonpickle](http://jsonpickle.github.io/) - Library for serializing any arbitrary object graph.
* [metamagic.json](https://pypi.org/project/metamagic.json/) - An ultra-fast Python 3 implementation of a JSON encoder.

**Ruby**
* [oj](https://github.com/ohler55/oj) - A fast JSON parser and Object marshaller as a Ruby gem. :star:2368
* [MultiJSON](https://github.com/intridea/multi_json) - A generic swappable back-end for JSON handling. :star:658

**React**
* [json2react](https://github.com/txgruppi/json2react) - Use JSON to create React Stateless Components. :star:152

**.NET**
* [jsonfx](https://github.com/jsonfx/jsonfx) - serialization framework for .NET. :star:372

**Scala**
* [spray-json](https://github.com/spray/spray-json) - A lightweight, clean and simple implementation in Scala. :star:841
* [circe](https://github.com/circe/circe) - Yet another JSON library for Scala. :star:1731
* [scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON:API spec with Play, Spray and/or Circe backends. :star:109
* [jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs. :star:247

**Swift**
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with data in Swift. :star:18759

## Linters
* [jsonlint](https://github.com/zaach/jsonlint) - Parser and validator with a CLI. (Javascript) :star:1484
* [JSON Lint](https://github.com/Seldaek/jsonlint) - PHP linter. (PHP) :star:887

## Online tools
* [JSONLint](https://jsonlint.com/) - The JSON Validator.
* [JSONCompare](https://jsoncompare.com/) - The Advanced Version of the JSON Linter.
* [JSONMate](http://jsonmate.com/) - JSON editor, inspector and beautifier.
* [JSON Editor online](http://jsoneditoronline.org/) - A web-based tool to view, edit and format.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - Formatter and Colorer of Raw Code.
* [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - Formatter to help with debugging.
* [JSON Generator](https://www.json-generator.com/) - Tool for generating random data.
* [FakeJSON](https://fakejson.com/) - Web API to quickly generate fake data for your application. 
* [JSON to CSV](https://konklone.io/json/) - A free, in-browser JSON to CSV converter. 
* [CSV to JSON](https://mango-is.com/tools/csv-to-json/) - Easy, privacy-friendly and offline-first online csv to json converter
* [json2csharp](http://json2csharp.com/) - Generate c# classes from a json string or url.
* [JSON Utils](http://jsonutils.com/) - Site for generating C#, VB.Net, and Javascript classes from JSON.
* [geojson.io](http://geojson.io/) - Simply edit GeoJSON map data.
* [jq play](https://jqplay.org/) - A playground for jq.
* [json2yaml](https://www.json2yaml.com/) - Convert JSON to YAML online.
* [JSON Selector Generator](http://jsonselector.com/) - A simple GUI for generating the selectors to access.
* [JSON.fr](https://www.json.fr/) - Fully client-side validator and formatter.
* [ObjGen](http://www.objgen.com/json) - Online live JSON generator.
* [JsonStub](https://jsonstub.com/) - Online JSON faker.
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake Online REST API for Testing and Prototyping.
* [Extends Class](https://extendsclass.com/json-diff.html) - Diff tool to compare two files.
* [JSON Schema Validate API](https://assertible.com/json-schema-validation) - A simple and free JSON Schema Validation API.

## Schema Specifications
* [JSON Schema](http://json-schema.org/) - a JSON based format for defining the structure of JSON data.
* [Itemscript](http://itemscript.org/ItemscriptSchema.html) - Language for validating and specifying values.
* [Kwalify](http://www.kuwata-lab.com/kwalify/) - A parser, schema validator, and data binding tool
* [Rx](http://rx.codesimply.com/) - Simple, Extensible Schemata.

## Services
* [Exchange Rate API](https://www.exchangerate-api.com) - A simple and free API for currency exchange rate data.
* [ipinfo.io](https://ipinfo.io) - JSON IP and GeoIP REST API.
* [JSONProxy](https://github.com/afeld/jsonp) - Simple HTTP proxy that enables cross-domain requests to any JSON API. :star:263
* [Myjson](http://myjson.com/) - A simple store for your web or mobile app.
* [Telize](http://www.telize.com/) - JSON IP and GeoIP REST API.
* [jsonpad](https://jsonpad.io/) - a simple JSON storage platform.
* [JSONP Proxy](https://github.com/fcambus/jsonp-proxy) - A REST API allowing to get JSONP from any API. :star:10

## Supersets
* [YAML](https://yaml.org) - A human friendly data serialization standard for all programming languages.
* [HanSON](https://github.com/timjansen/hanson) - JSON for Humans - with unquoted identifiers, multi-line strings and comments. :star:136
* [μson](https://github.com/burningtree/uson) (uson) - a shorthand for JSON. :star:62
* [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) - Human-Optimized Config Object Notation. :star:4423
* [ASON](http://www.americanteeth.org/libason/ason_spec.pdf) - A semantically complete superset of JSON (draft).
* [TOML](https://github.com/toml-lang/toml) - A minimal configuration file format that's easy to read due to obvious semantics. :star:11644
* [HCL](https://github.com/hashicorp/hcl) - A structured configuration language that is both human and machine friendly. :star:2440

## Tutorials
* [Introducing JSON](http://json.org/)
* [JSON Tutorial](https://www.w3resource.com/JSON/introduction.php) - An introductory tutorial on JavaScript Object Notation (JSON).
* [JSON - Rosetta Code](http://rosettacode.org/wiki/JSON) - Basic operations in different languages (57 languages in this moment).
* [What is JSON and how to use it](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - Video tutorial for beginners.
* [jq Primer: Munging JSON Data](http://andrew.gibiansky.com/) - How jq can be used to process JSON files just as effectively as traditional Unix tools.

## Related formats
* [AXON](https://intellimath.bitbucket.io/axon/) - A simple text based format for interchanging of objects, documents and data. It tries to combine the best of JSON, XML and YAML.
* [CSON](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. JSON for CoffeeScript objects. :star:1202
* [MSON](https://github.com/apiaryio/mson) - Markdown syntax compatible with describing JSON and JSON Schema. :star:782
* [ArchieML](http://archieml.org/) - Structured text format optimized for human writability.

## Resources
* [Type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability, comparison of different JS type systems and conversion between them. :star:171
* [Awesome jq](https://github.com/fiatjaf/awesome-jq) - A curated list of awesome jq tools and resources. :star:224

## Templates
* [Jsonnet](https://jsonnet.org/) - A domain specific configuration language that helps you define JSON data.
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support. (Ruby) :star:3583
* [json2html](http://json2html.com/) - HTML templating library with wrappers for both jQuery and Node.js. (Javascript)

## Testing
* [JSON Test](http://www.jsontest.com/) - Testing platform for services utilizing JavaScript Object Notation (JSON).
* [JSONassert](https://github.com/skyscreamer/JSONassert) - Write JSON unit tests in less code. Great for testing REST interfaces. (Java) :star:630
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit) - A library that simplifies JSON comparison in unit tests. It's strongly inspired by XmlUnit. :star:369

## Text Editor Plugins
**Emacs**
* [JSON Reformat](https://github.com/gongo/json-reformat) - Reformat tool. :star:149

**Vim**
* [vim-json](https://github.com/elzr/vim-json) - A better JSON for Vim: distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing. Pathogen-friendly. :star:1085

## Transformations
* [json-sharp](https://github.com/globocom/json-sharp) - Javascript tool to process operations on pure JSON objects. (Javascript) :star:4
* [json2json](https://github.com/joelvh/json2json) - Transform (reformat) structures from one to another. (Javascript) :star:177
* [trans](https://github.com/gabesoft/trans) - The ultimate object transformer. (Javascript) :star:176
* [osmtogeojson](https://github.com/tyrasd/osmtogeojson) - Converts OSM data to GeoJSON. (Javascript) :star:385
* [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - Fast XML to JSON and vice versa javascript/JSON conversion. :star:517
* [x2js](https://github.com/abdolence/x2js) - XML to JSON and vice versa javascript conversion functions. (Javascript) :star:766
* [JSONC](https://github.com/tcorral/JSONC) - JSON compressor and decompressor. (Javascript) :star:523
* [JsonMapper](https://github.com/cweiske/jsonmapper) - Map nested structures onto PHP classes (PHP) :star:1005
* [SassyJSON](https://github.com/HugoGiraudel/SassyJSON) - Sass-powered API. (Sass) :star:171
* [json.human.js](http://marianoguerra.github.io/json.human.js/) - A small library to convert a JSON object into a human readable HTML representation that is easy to style for different purposes.
* [JSONtoFoundation](https://github.com/fmscode/JSONtoFoundation) - OS X utility that converts a JSON object to a Foundation object that can be used in Cocoa/Cocoa Touch development. (Swift) :star:42
* [fanci](https://github.com/liip/fanci) - Extract, rename and transform JSON based on a template. (node.js) :star:20
* [Pinch](https://github.com/Baggz/Pinch) - String.replace for JavaScript objects. (Javascript) :star:23
* [deepjson](http://deepjson.jacoborus.codes/) - A better way to load big json config files. (node.js)
* [jsontl](https://github.com/DoublePrecisionSoftware/jsontl) - allow transformation using a JSON-based transformation language. (node.js) :star:6
* [json-transforms](https://github.com/ColinEberhardt/json-transforms) - A recursive, pattern-matching, approach to transforming JSON structures. :star:78
* [normalizr](https://github.com/paularmstrong/normalizr) - Normalizes nested JSON according to a schema. (Javascript) :star:17395
* [JSON-populate](https://github.com/eiriklv/json-populate) - Tool for populating JSON data with infinitely recursive circular references. Sort of like Falcor, but for plain JSON. :star:82
* [CircularJSON](https://github.com/WebReflection/circular-json) - JSON does not handle circular references. Now it does. :star:559
* [Sawmill](https://github.com/logzio/sawmill) - JSON transformation library (Java) :star:58
* [nimnjs](https://github.com/nimndata/nimnjs) - JSON to nimn bidirectional converter. :star:32

## Queries
* [JMESPath](http://jmespath.org/) - A query language for JSON.
* [JSON Mask](https://github.com/nemtsov/json-mask) - Tiny language and engine for selecting specific parts of a JS object, hiding the rest. (Javascript) :star:539
* [JSONiq](http://www.jsoniq.org/) - The JSON Query Language.
* [ObjectPath](http://objectpath.org/) - The agile query language for semi-structured data. (Python)
* [DefiantJS](https://www.defiantjs.com/) - Lightning-fast searches using XPath expressions, and transform using XSL. (Javascript)
* [JSONSelect](https://github.com/lloyd/JSONSelect) - CSS-like selectors. (Javascript) :star:1594
* [JSONPath](https://goessner.net/articles/JsonPath/) - XPath implementation. (Javascript/PHP)
* [searchjs](https://github.com/deitch/searchjs) - A library for filtering based on a json SQL-like language. :star:235
* [json-rel](https://github.com/slurmulon/json-where) - Transparent references in JSON. :star:9
* [JSONata](http://jsonata.org/) - Query and transformation language used in Node-RED, supports function expressions.

## JSON Schema Frontend components
* [JSON Editor](https://github.com/jdorn/json-editor) - JSON Schema Based Editor. (jQuery) :star:5201
* [angular-schema-form](https://github.com/json-schema-form/angular-schema-form) - Generate forms. (AngularJS) :star:2376
* [JSON Schema View](https://github.com/mohsen1/json-schema-view) - An AngularJS directive for rendering JSON Schema in HTML (AngularJS) :star:43
* [Angular JSON Schema Form](https://github.com/mohsen1/angular-json-schema-form) - Angular directive for making forms out of JSON Schema. (AngularJS) :star:31
* [AlpacaJS](http://www.alpacajs.org) - Generates JSON Schema driven forms on top of Bootstrap, jQuery Mobile, jQuery UI and HTML (jQuery)


## JSON Schema Tools
* [prmd](https://github.com/interagent/prmd) - Tools and doc generation for HTTP APIs. :star:2000
* [generate-schema](https://github.com/Nijikokun/generate-schema) - Effortlessly convert your JSON Object to JSON Schema, Mongoose Schema, or a Generic template for quick documentation / upstart. :star:628
* [Docson](https://github.com/lbovet/docson) - Documentation for your types. :star:425
* [Orderly JSON](https://github.com/lloyd/orderly) - A textual format for describing JSON compiled into JSONSchema. :star:198
* [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Generates Java types and annotates those types for data-binding with Jackson 1.x or 2.x, Gson, etc. :star:4642
* [Matic](https://github.com/mattyod/matic) - Build tool for generating HTML documentation. :star:161
* [JSON Schema + Faker](https://github.com/json-schema-faker/json-schema-faker) - Fake your schemas. :star:1969
* [DLL.js](https://github.com/moll/js-ddl) - Gets you a JSON Schema from PostgreSQL or SQLite3. :star:60
* [JSONSchema.net](https://jsonschema.net//) - JSON Schema generator from JSON object.
* [js-schema](https://github.com/molnarg/js-schema) - A new way of describing object schemas in JavaScript. It has a clean and simple syntax, and it is capable of serializing to/from the popular JSON Schema format. :star:370
* [aptos](https://github.com/pennsignals/aptos) - A tool for validating data using JSON Schema and converting JSON Schema documents into different data-interchange formats. :star:139
* [JSON Schema $Ref Parser](https://github.com/APIDevTools/json-schema-ref-parser) - Parse, resolve, and dereference JSON Schema $ref pointers :star:307

## JSON Schema Resources
* [Understanding JSON Schema](https://spacetelescope.github.io/understanding-json-schema/) - A website aiming to provide more accessible documentation for JSON schema.
* [JSON Schema Store](http://schemastore.org/json/) - A collection of popular schemas.
* [Using JSON Schema](http://usingjsonschema.com/) - a Book and GitHub project, showing how JSON Schema can be used for a variety of tasks and in different programming contexts.

## JSON Schema Validators
**Javascript and Node.js**
* [json-schema-benchmark](https://github.com/ebdrup/json-schema-benchmark) - Performance benchmark for Node.js validators. :star:290
* [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - A validator that uses code generation to be extremely fast. :star:876
* [jsen](https://github.com/bugventure/jsen) - A validator built for speed. :star:148
* [themis](https://github.com/playlyfe/themis) - A blazing fast validator. :star:58
* [jsck](https://github.com/pandastrike/jsck) - JSON Schema Compiled checK. :star:158
* [z-schema](https://github.com/zaggino/z-schema) - validator written in JavaScript for NodeJS and Browsers. :star:270
* [jjv](https://github.com/acornejo/jjv) - Javascript Library for Schema Validation. :star:191
* [request-validator](https://github.com/bugventure/request-validator) - Flexible request validator middleware for express and connect.
* [tv4](https://github.com/geraintluff/tv4) - Tiny Validator. :star:1066
* [ajv](https://github.com/epoberezkin/ajv) - The fastest validator. Supports v5/6 proposals. :star:6016


**PHP**
* [JSON Schema for PHP](https://github.com/justinrainbow/json-schema) - PHP implementation of JSON schema. :star:2306
* [JSON Guard](https://json-guard.thephpleague.com) - A validator for JSON Schema Draft 4.

**Python**
* [jsonschema](https://github.com/Julian/jsonschema) - Python implementation of jsonschema. :star:2405
* [JSON Schema Toolkit](https://github.com/petrounias/json-schema-toolkit) - Programmatic building of JSON schemas (recursive field mappings) with validation, a Django JSON Field, and native PostgreSQL JSON type constraints. :star:27

**Ruby**
* [Ruby JSON Schema Validator](https://github.com/ruby-json-schema/json-schema) - validating against a JSON schema conforming to JSON Schema Draft 4. :star:1110

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

