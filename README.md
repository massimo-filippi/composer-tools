# Composer Tools

## Introduction

There will be more info soon...

## Installation

Install the latest stable version via Composer:

```
composer require massimo-filippi/composer-tools
```

Install the latest develop version via Composer:

```
composer require massimo-filippi/composer-tools:dev-develop
```

## Usage

### Compile translations

To compile .po files to .mo files use the following console command from root of the project:

```
vendor/bin/compile-translations
```

Output of the script should be as following:

```
Start compiling .mo files
Compiling file: language/cs_CZ/application.po
Compiling file: language/de_DE/application.po
Compiling file: language/sk_SK/application.po
Compiled.
```
