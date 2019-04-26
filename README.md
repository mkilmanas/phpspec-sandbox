# phpspec-sandbox
Bare sandbox for rapid setup of phpspec-only playground

### Pre-requisites
- PHP 7.1+
- composer

### Setup
```bash
composer install
```

### Usage

```bash
bin/phpspec desc Acme/Foo/Bar

bin/phpspec r
```

### Namespaces
This sandbox is preconfigured to use `src/` directory as `Acme\\` namespace, so you are encouraged to use this namespace prefix.

Otherwise, please feel free to define your own namespaces in `composer.json` and `phpspec.yml`