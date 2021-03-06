# Jasmine Reporters

Jasmine Reporters is a collection of javascript jasmine.Reporter classes that can be used with
the [JasmineBDD testing framework](http://pivotal.github.com/jasmine/).

Included reporters:

* JUnitXmlReporter - Report test results to a file in JUnit XML Report format.
* NUnitXmlReporter - Report test results to a file in NUnit XML Report format.
* TapReporter - Test Anything Protocol, report tests results to console.
* TeamcityReporter - Basic reporter that outputs spec results to for the Teamcity build system.
* TerminalReporter - Logs to a terminal (including colors) with variable verbosity.

## Usage

Examples are included in the test directory that show how to use the reporters,
as well a basic runner for [PhantomJS](https://github.com/ariya/phantomjs).

### PhantomJS

Should work in most versions of PhantomJS > 1.4.1
I have used PhantomJS 1.4.1 through 1.9.6 on Mac OS X with no problems.

### Node.js

Most of these reporters also work in node.js by making use of the excellent
[jasmine-node project](https://github.com/mhevery/jasmine-node).
