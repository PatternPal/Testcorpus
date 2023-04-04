# PatternPal Test Corpus
This repository contains many implementations of design patterns in C#, which can be used to test
[PatternPal]. Using the [test runner], the PatternPal recognizers can be tested on the
implementations in this repository. The tool will provide precision and recall statistics, which are
an indication of how well the recognizer works. A configuration file can be used to configure the
[test runner].

## Usage
The test runner tool takes one argument, the config file to use:
```shell
PatternPal.TestRunner.exe --config Configs/all.json
```

[PatternPal]: https://github.com/PatternPal/PatternPal
[test runner]: https://github.com/PatternPal/PatternPal/tree/a61e045faab2a98ab7235b2ff9a4fc555578b9cd/PatternPal/PatternPal.TestRunner
