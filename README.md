# Laravel Project Template

## Installation

You can install the package via composer:

```bash
composer require dbt/laravel-project
```

But it's more likely you'll want to use this as a template. Use GitHub's "Use this template" button to do that.

## Usage

Change the project name and namespaces in `composer.json`, `UnitTestCase`, `IntegrationTestCase`, and `ServiceProvider`. Copy `phpunit.xml.dist` to `phpunit.xml` and update the environment values to fit your project. Run `composer dump-autoload` and you should be ready to go.

If you wish to change the name of `ServiceProvider`, keep in mind that the reference in your `IntegrationTestCase` must be changed as well. 

## Etc.

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.
The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
