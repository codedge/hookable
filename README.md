# codedge/hookable

Improved version of [Jarek Tkaczyk](https://github.com/jarektkaczyk/hookable) superb hook system for Laravel.

Hooks are available for the following methods:
* `Model::getAttribute`
* `Model::setAttribute`
* `Model::save`
* `Model::toArray`
* `Model::replicate`
* `Model::isDirty`
* `Model::__isset`
* `Model::__unset`

and all methods available on the `Illuminate\Database\Eloquent\Builder` class.

**Additional hooks, mostly for all relation types, are:**
* `Model::hasOne`

## Installation

Clone the repo or pull as composer dependency:

```
composer require codedge/hookable
```

## Usage
Please see the [original package](https://github.com/jarektkaczyk/hookable) for usage.