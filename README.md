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
# Describe a new class
bin/phpspec desc Acme/Foo/Bar

# Run the tests
bin/phpspec r
```

If you are using this for a code kata, you may find the helper script useful
```bash
bin/reset
```
It will delete all the code from `src/` and `spec/` directories, so your are read for the next session in an eye-blink

### Namespaces
This sandbox is preconfigured to use `src/` directory as `Acme\\` namespace, so you are encouraged to use this namespace prefix.

Otherwise, please feel free to define your own namespaces in `composer.json` and `phpspec.yml`