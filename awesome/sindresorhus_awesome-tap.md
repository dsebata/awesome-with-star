# Information comes from [sindresorhus/awesome-tap](https://github.com/sindresorhus/awesome-tap)
# Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)


> Useful resources for the [Test Anything Protocol](https://testanything.org)<br>
> A simple text-based interface between testing modules in a test harness

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*


## Contents

- [Reporters](#reporters)
- [Producers](#producers)
- [Consumers](#consumers)
- [Tools](#tools)
- [Articles](#articles)
- [Tutorials](#tutorials)
- [Documentation](#documentation)
- [Community](#community)


## Reporters

### JavaScript

- [tap-dot](https://github.com/scottcorgan/tap-dot) - Dotted output. :star:30
- [tap-spec](https://github.com/scottcorgan/tap-spec) - Mocha-like spec reporter. :star:256
- [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) - Nyan cat. :star:138
- [tap-min](https://github.com/gummesson/tap-min) - Minimal output. :star:28
- [tap-difflet](https://github.com/namuol/tap-difflet) - Minimal output with diffing. :star:43
- [tap-diff](https://github.com/axross/tap-diff) - Human-friendly output with diffing. :star:76
- [tap-simple](https://github.com/joeybaker/tap-simple) - Simple output. :star:6
- [faucet](https://github.com/substack/faucet) - Human-readable summarizer. :star:516
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - Use any of the [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters). :star:15
- [tap-summary](https://github.com/zoubin/tap-summary) - Summarized output. :star:35
- [tap-pessimist](https://github.com/clux/tap-pessimist) - Only shows failed tests. :star:14
- [tap-prettify](https://github.com/toolness/tap-prettify) - Nice readable output with diffing. :star:31
- [tap-colorize](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability. :star:30
- [tap-bail](https://github.com/juliangruber/tap-bail) - Bail out when the first test fails. :star:18
- [tap-notify](https://github.com/axross/tap-notify) - Notifier for macOS, Linux and Windows. :star:58
- [tap-json](https://github.com/gummesson/tap-json) - JSON output. :star:21
- [ava-tap-json](https://github.com/yovasx2/ava-tap-json) - JSON output with AVA compatibility. :star:1
- [tap-xunit](https://github.com/aghassemi/tap-xunit) - xUnit output. :star:31
- [tap-teamcity](https://github.com/smockle/tap-teamcity) - Output for TeamCity. :star:8


## Producers

Things that produce TAP output.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - Futuristic test runner (`$ ava --tap`). :star:16661
- [tap](https://github.com/isaacs/node-tap) - TAP test framework for Node.js. :star:1430
- [tape](https://github.com/substack/tape) - TAP-producing test harness for Node.js and browsers. :star:5090
- [ESLint](http://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter (`$ eslint --format=tap`).
- [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers (`$ mocha reporter=tap`).
- [qunit-tap](https://github.com/twada/qunit-tap) - TAP output for QUnit. :star:73
- [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) - TAP output for Jasmine. :star:398
- [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) - TAP output for Karma. :star:7
- [mos](https://github.com/zkochan/mos) - Markdown file generator and tester (`$ mos test --tap`). :star:104

### Fish

- [Fishtape](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish. :star:235

### Bash

- [bats](https://github.com/sstephenson/bats) - Bash Automated Testing System. :star:5861

[More...](https://testanything.org/producers.html)


## Consumers

Things that consume TAP output.

### JavaScript

- [tap-parser](https://github.com/substack/tap-parser) - TAP parser. :star:93
- [tap-out](https://github.com/scottcorgan/tap-out) - TAP parser. :star:20
- [yamlish](https://github.com/isaacs/yamlish) - YAML-block parser. :star:20

[More...](https://testanything.org/consumers.html)


## Tools

### JavaScript

- [tap-dev-tool](https://github.com/Jam3/tap-dev-tool) - Prettify TAP in the browser console. :star:28
- [tap-merge](https://github.com/anko/tap-merge) - Merge multiple TAP streams. :star:10
- [smokestack](https://github.com/hughsk/smokestack) - Run TAP tests in a browser and write the output to `stdout`. :star:240
- [chutney](https://github.com/derhuerst/chutney) - Run TAP tests at Sauce Labs. Lightweight [smokestack](https://github.com/hughsk/smokestack) alternative. :star:5

### Python

- [tappy](https://github.com/mblayman/tappy) - Tools for working with TAP. :star:70


## Articles

- [Understand the Test Anything Protocol](http://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)


## Tutorials

- [test-anything](https://github.com/finnp/test-anything) - Learn to test anything with TAP through an interactive workshop. :star:139


## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)


## Community

- [Discuss](https://github.com/TestAnything/Specification/issues) :star:49
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/tap)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.

