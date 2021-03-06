.. :changelog:

History
=======

1.5.4
=====

* Stop returning gzipped file when using GZIPMixin.
* Fix jinja templates packaging.

1.5.3
=====

* Fix futures import. Thanks to Mathieu Gallet.
* Make GZIPMixin returns the gziped file.
* Fix import shadowing. Thanks to Christofer Bertonha.
* Fix tests settings for Django 1.9. Thanks to Leonardo Orozco.
* Improve javascript concatenation. Thanks to Simon Lydell and Alex Gavrișco.
* Improve finder logic. Thanks to Nathan Shafer and James Keys.
* Documentation fix. Thanks to Stefano Brentegani.

1.5.2
=====

* Use smart_bytes and smart_text appropriately. Thanks to Tadas Dailyda.
* Fix outdated logic. Thanks to Tadas Dailyda.

1.5.1
=====

* Prevent collecting all static multiple times per request. Thanks to Allard Stijnman.
* Fix encoding issues. Thanks to Leonardo Orozco.
* Improve Django 1.8. Thanks to Carl Meyer.

1.5.0
=====

* Add full support for Django 1.8.
* Drop support for Django 1.6.
* Drop support for Python 2.6.
