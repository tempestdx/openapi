# Tempest OpenAPI specs

[![Go Reference](https://pkg.go.dev/badge/github.com/tempestdx/openapi)](https://pkg.go.dev/github.com/tempestdx/openapi)
[![Test Status](https://github.com/tempestdx/openapi/actions/workflows/go.yml/badge.svg?branch=main)](https://github.com/tempestdx/openapi/actions/workflows/go.yml?query=branch%3Amain)

This repository contains OpenAPI specifications for [Tempest][tempest] API.

## Tempest API

Unlock Tempest's full potential with our flexible API, enabling seamless
integration, custom workflows, automation, and adaptability across any tech
stack in any language.

## Generating Go code:

To generate Go code from the OpenAPI spec, you can use the `oapi-codegen` tool.

```sh
go run github.com/oapi-codegen/oapi-codegen/v2/cmd/oapi-codegen --config=app/config.yaml app/app.yaml
```

## Documentation

For details on all of the functionality, see our
[API documentation][openapi-docs].

To share any requests, bugs or comments, please [open an issue][issues] or
[submit a pull request][pulls].

[issues]: https://github.com/tempestdx/openapi/issues/new
[pulls]: https://github.com/tempestdx/openapi/pulls
[tempest]: https://tempestdx.com/
[openapi-docs]: https://docs.tempestdx.com/developer/api
