Changelog
=========

0.8.3 (2022-01-15)
------------------

* Update all dependencies, fixing a potential upstream security bug
  in `json-pointer`.


0.8.2 (2021-05-28)
------------------

* Switch from `better-ajv-errors` to `@stoplight/better-ajv-errors`. The
  former no longer appears to be maintained.


0.8.1 (2021-05-18)
------------------

* Add an option to *not* automatically add a HTTP Link header.


0.8.0 (2021-02-15)
------------------

* Now an official Curveball package.
* Renamed from `@badgateway/schema-api` to `@curveball/validator`.
* Remove stateful API (`addSchemasForDir`, `schemaValidate` functions).


0.6.1 (2021-02-01)
------------------

* Fix validation method.


0.6.0 (2021-01-31)
------------------

* Rewrote parts of the library to behave more like a middleware. The validator
  can now be found in `ctx.request.validate()`.
* The middleware automatically creates a 'schema collection', mounted under
  `/schema`, and also creates a link from the home document for easy discovery.


0.5.0 (2021-01-31)
------------------

* Validator can now run more than once.


0.4.0 (2021-01-14)
------------------

* Include 'ajv-formats'.


0.3.0 (2021-01-14)
------------------

* Switch to JSON-Schema 2019-09 draft.


0.2.0 (2021-01-14)
------------------

* Upgrade to Ajv 7


0.1.0 (2021-01-14)
------------------

* Bug: Validation didn't work.


0.0.3 (2021-01-14)
------------------

* Re-release of 0.0.2.


0.0.2 (2021-01-14)
------------------

* First version
