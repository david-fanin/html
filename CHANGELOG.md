# Changelog

This changelog references the relevant changes (bug and security fixes) done to `html`.

## 5.1.2 - 2015-11-19

### New

* Add `Form::datetime` helper method.
* Add `Form::datetimeLocal` helper method.

## 5.1.1 - 2015-11-06

### Changes

* Remove requirement to assign CSRF token from the Service Provider as it might be loaded before session middleware is ready.
* Don't depends on concretes `UrlGenerator` in `Collective\Html\FormBuilder`.
* `HTML::dl()` now supports multiple descriptions per term.
* first character capitalization in month names for `Form::selectMonth()`.
 
## 5.1.0 - 2015-11-02

### New

* Fork the base HTML package from <https://github.com/laravelcollective/html>.
* Add following traits:
  - `Collective\Html\Traits\CheckerTrait`
  - `Collective\Html\Traits\CreatorTrait`
  - `Collective\Html\Traits\InputTrait`
  - `Collective\Html\Traits\ObfuscateTrait`
  - `Collective\Html\Traits\SelectionTrait` 
  - `Collective\Html\Traits\SessionHelperTrait` 

