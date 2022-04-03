## Berlin Anmeldung Finder

Check for available Anmeldung appointment (apartment registration) in Berlin.

### Installation

1. Check you have a PHP version 8.0 or higher

2. Require the project and install dependencies
```bash
composer require jesusvalera/berlin-anmeldung
```

```bash
cd berlin-anmeldung
composer install
```

3. Duplicate the `config/default.php` file into a new one with `config/default.php` name. You can modify the content of this new file.

4. Run the project
```bash
php anmeldung
```

### Project structure

This is the project structure. See more [about gacela here](https://gacela-project.com/about-gacela/).

```bash
anmeldung-berlin
├── anmeldung         # Entry point of the application
│
├── config
│   ├── default.php
│   └── local.php     # Create this file with your specific data from `default.php` file.
│
├── src
│   └── Anmeldung
│       ├── Domain
│       │   └── ...
│       ├── AnmeldungFacade.php
│       └── AnmeldungFactory.php
│       ├── AnmeldungConfig.php
│
├── tests
│   └── ...
└── vendor
    └── ...
```
