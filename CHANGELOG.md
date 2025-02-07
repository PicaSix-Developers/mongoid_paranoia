## 0.6.0 (2023/01/09)

* Now supports mongoid 7.3 to 8.x.x versions.

## 0.5.0 (2021/07/24)

* Support only Mongoid 7.3 and later.
* In conformity with Mongoid 7.3+ behavior, dependencies are not destroyed when calling delete/delete!

## 0.4.1 (2021/07/24)

* Do not allow Mongoid 7.3 and later, due to breaking changes
* Switch to Github Actions from Travis CI
* Add Rubocop and fix issues
* Dropped Ruby < 2.4

## 0.4.0 (2019/05/29)

* Mongoid 7.0 support
* Drop Mongoid 6 and Ruby < 2.3

## 0.3.0 (2017/01/05)

* Mongoid 6.0 support
* Drop Mongoid 4/5 and Ruby < 2.2.2

## 0.2.1 (2015/09/28)

* [#40](https://github.com/simi/mongoid_paranoia/pull/40): Don't override mongoid original update - [@simi](https://github.com/simi).

## 0.2.0 (2015/09/22)

* [#38](https://github.com/simi/mongoid_paranoia/pull/38): Added support for Mongoid 5 - [@dblock](https://github.com/dblock).
* [#29](https://github.com/simi/mongoid_paranoia/pull/29): Added `before_remove`, `after_remove` and `around_remove` callbacks - [@marcelloma](https://github.com/marcelloma).
* [#34](https://github.com/simi/mongoid_paranoia/pull/34): Allow configuring of the paranoid field naming on a global basis - [@ak47](https://github.com/ak47).

## 0.1.2 (2014/07/11)

* Initial public release - [@simi](https://github.com/simi).
