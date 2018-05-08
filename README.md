# Laravel Validator Rules - Exposed Password

This rule will validate that a password hasn't been exposed in a data breach.

## Installation

```bash
composer require laravel-validation-rules/exposed-password
```

## Usage

```php
use DivineOmega\LaravelPasswordExposedValidationRule\PasswordExposed;

$request->validate([
    'password' => ['required', new PasswordExposed],
]);
```

## License
This project is licensed under a GNU Lesser General Public License v3.0 which you can find
[in this LICENSE](https://github.com/laravel-validation-rules/exposed-password/blob/master/LICENSE).


## Feedback
If you have any feedback, comments or suggestions, please feel free to open an
issue within this repository.

## Laravel Validation Rules

This package is part of the Laravel Validation Rules collection. If you're after more Laravel Validation Rules, head to the [Laravel Validation Rules](https://laravel-validation-rules.github.io/) website.