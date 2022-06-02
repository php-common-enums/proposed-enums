# Introduction

Thank you for considering contributing to PHP Common Enums.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

# How to report a bug

Please create a GitHub Issue in the repository of the enum that has the bug.

# How to fix a bug or improve an enum

Please create a GitHub Pull Request in the repository of the enum that you want to fix or improve.

# How to suggest a new backed enum

Please create a GitHub Issue or and GitHub Pull Request in the [php-common-enums/proposed-enums](https://github.com/php-common-enums/proposed-enums/pulls) repository if you want to suggest a new backed enum that we should add as a separate repository/library in the collection.

The proposed enum must:

- be a PHP backed enum,
- have the potential for common use,
- be relatively stable and not subject to frequent change.

# Coding standards

If you use [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer), then apply the [Symfony rules](https://cs.symfony.com/doc/ruleSets/Symfony.html) to the enum class.

```bash
php php-cs-fixer fix /path/to/project --rules=@Symfony
```