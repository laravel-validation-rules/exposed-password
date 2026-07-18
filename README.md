# Laravel Validator Rules - Exposed Password

This metapackage installs the maintained Laravel rule that validates that a password has not been exposed in a data breach.

## Installation

```bash
composer require laravel-validation-rules/exposed-password
```

## Usage

```php
use JordJD\LaravelPasswordExposedValidationRule\PasswordNotExposed;

$request->validate([
    'password' => ['required', new PasswordNotExposed()],
]);
```

Version 2 of this metapackage uses the current `jord-jd/laravel-password-exposed-validation-rule` package and namespace. Applications that still use the legacy `DivineOmega` namespace should remain on version 1 until they are ready to update the import.

## License
This project is licensed under a GNU Lesser General Public License v3.0 which you can find
[in this LICENSE](https://github.com/laravel-validation-rules/exposed-password/blob/master/LICENSE).


## Feedback
If you have any feedback, comments or suggestions, please feel free to open an
issue within this repository.

## Laravel Validation Rules

This package is part of the Laravel Validation Rules collection. If you're after more useful validation rules, head to the [Laravel Validation Rules](https://laravel-validation-rules.github.io/) website.
