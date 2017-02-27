# Static code analysis for php/composer projects using Phing

This is a Phing build file that I generally use to run static code analysis tools and phpunit in my composer projects.

It runs:
* PHP Lint.
* PHP CodeSniffer for PSR2 standard.
* PHPMD for unusedcode, codesize, controversial, design, naming rules.
* PHP Copy Paste detector.
* PHP LOC.
* PHP Depend.
* PHPUnit + Codecoverage.
* PHPDocumentor.
 
All results are saved inside phing-build directory.

### Requirements:
* php
* phing/phing
* squizlabs/php_codesniffer
* phpmd/phpmd
* sebastian/phpcpd
* pdepend/pdepend
* phpunit/phpunit
* phpdocumentor/phpdocumentor
* ext-xsl (It requires php extension xsl to generate coverage html report).

See [mcustiel/docker-php-tools](https://github.com/mcustiel/docker-php-tools), you can find all need tools there..
