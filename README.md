# Static code analysis for php/composer projects using Phing

This is a Phing build file that I generally use to run static code analysis tools and phpunit in my composer projects.

It runs:
* PHP Lint.
* PHP CodeSniffer for PSR2 standard.
* PHPMD for unusedcode, codesize, controversial, design, naming rules.
* PHP Copy Paste detector.
* PHP LOC.
* PHPUnit + Codecoverage.
 
All results are saved inside phing-build directory.
