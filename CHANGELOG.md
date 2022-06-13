## 2.0.0 2022-??-??

- [#26]((https://github.com/luolingchun/flask-openapi3/issues/26)) fix: Body throws exception when receiving str instead of dict. Thanks @nor3th
- [#17](https://github.com/luolingchun/flask-openapi3/issues/17) Support for Nested APIBlueprint enhancement. Thanks @dvaerum
- [#23](https://github.com/luolingchun/flask-openapi3/pull/23) Fixed externalDocs support. Thanks @dvaerum
- Add `flask openapi` command
- add options in view functions
- Support for empty response body. Thanks @dvaerum
- Upgrade flask to v2.0

### Breaking Changes

- Remove export markdown to `flask openapi` command

## v1.1.4 2022-05-05

- fix: Trailing slash in APIBlueprint

## v1.1.3 2022-05-01

- fix: Find globalns for the unwrapped func
- [#19](https://github.com/luolingchun/flask-openapi3/issues/19) fix: Trailing slash in APIBlueprint. Thanks @ev-agelos
- add description for UnprocessableEntity
- remove printouts in `__init__.py`

## v1.1.2 2022-04-01

- [#16](https://github.com/luolingchun/flask-openapi3/issues/16) Fix fileStorage list is not supported. Thanks @tekrei

## v1.1.0 2022-03-13

- [#13](https://github.com/luolingchun/flask-openapi3/issues/13) drop support for flask 1.0.x. Thanks @danmur
- [#15](https://github.com/luolingchun/flask-openapi3/pull/15) Fix to enable BaseModel with __root__ property. Thanks @tarcisiojr
- [#14](https://github.com/luolingchun/flask-openapi3/pull/14) Custom parameters: doc_prefix, api_doc_url, swagger_url, redoc_url, rapidoc_url. Thanks @barryrobison
- Upgrade swagger UI v4.6.2
- Upgrade Redoc v2.0.0-rc.63
- Upgrade RapiDoc v9.2.0

## v1.0.1 2022-02-12

- add operation_id for OpenAPI Specification

## v1.0.0 2022-01-11

- [#10](https://github.com/luolingchun/flask-openapi3/issues/10) Fix: header's title case. Thanks @rrr34
- [#9](https://github.com/luolingchun/flask-openapi3/issues/9) Support for extra responses. Thanks @blynn99
- [#12](https://github.com/luolingchun/flask-openapi3/pull/12) Support for path operation field deprecated. Thanks
  @blynn99
- Add keyword parameters `summary` and `description`
- Add servers for OpenAPI
- Upgrade swagger UI v4.1.3
- Upgrade Redoc v2.0.0-rc.59
- Add rapidoc

### Breaking Changes

- Renamed `securitySchemes` to `security_schemes`
- Renamed `docExpansion` to `doc_expansion`

## v0.9.9 2021-12-09

- fix: default value in query and form model
- fix: empty form and body
- support `from __future__ import annotations`
- drop python36

## v0.9.8 2021-11-12

- add Configuration `docExpansion`
- query and form add array support

## v0.9.7 2021-08-19

- fix: path $ref
- fix: markdown enum

## v0.9.6 2021-08-18

- Export to markdown(Experimental)

## v0.9.5 2021-07-11

- remove `validate_resp` and add `VALIDATE_RESPONSE`

## v0.9.4 2021-07-03

- OpenAPI add responses and APIBlueprint add abp_responses
- fix: validate response error when responses is empty dict
- [#3](https://github.com/luolingchun/flask-openapi3/issues/3) endpoint and APIBlueprint add `doc_ui`. Thanks
  @DerManoMann
- [#4](https://github.com/luolingchun/flask-openapi3/issues/4) fix: response description. Thanks @DerManoMann
- [#5](https://github.com/luolingchun/flask-openapi3/issues/5) add custom parameter `oauth_config`. Thanks @DerManoMann
- [#6](https://github.com/luolingchun/flask-openapi3/issues/6) support validation Flask Response. Thanks @DerManoMann
- [#7](https://github.com/luolingchun/flask-openapi3/issues/7) fix: response validation does not work when uses
  http.HTTPStatus enums as status_code. Thanks @DerManoMann

## v0.9.3 2021-06-08

- APIBlueprint add abp_tags and abp_security
- fix: tags de-duplication
- fix: operation summary and description

## v0.9.2 2021-05-17

- fix: _do_decorator
- add doc_ui args. support close swagger UI and redoc

## v0.9.1 2021-05-16

- fix：request data is None
- json-->body
- set 422 Content-Type application/json
- raise response validate exception
- fix: TypeError: issubclass() arg 1 must be a class

## v0.9.0 2021-05-13

- first version
