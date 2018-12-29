# phpcs-base-ruleset
A PHP CodeSniffer basic ruleset for my projects


## Usage

1. `composer require zgldh/phpcs-base-ruleset`
2. `cp vendor/zgldh/phpcs-base-ruleset/ruleset.template.xml ./ruleset.xml`
3. `vendor/bin/phpcs --standard=ruleset.xml`

You can integrate PHP_CodeSniffer into Jenkins or other CI/CD tools.
