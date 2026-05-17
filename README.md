# Meta OpenAPI Specifications


## Overview

This repository contains  [OpenAPI](https://www.openapis.org/what-is-openapi) specifications for Meta APIs. It's intended to formally describe a product area’s complete specification and is designed to be used to  generate [SDKs by Meta](https://developers.facebook.com/docs/business-sdk/getting-started) and others who wish to monitor and integrate Meta APIs into other tools.


### Composition

The repository currently contains specifications for:


* [Business Messaging - WhatsApp API OpenAPI Specification](https://github.com/facebook/openapi/blob/main/business-messaging-api_v23.0.yaml). Visit developer documentation for WhatsApp Business API [here](https://developers.facebook.com/documentation/business-messaging/whatsapp/overview).

> [!IMPORTANT]
> NOTE: Usage of the API are subject to additional Terms and Conditions.

## Contributing / Making changes

This repository contains OpenAPI YAML specifications. A good first contribution is often improving documentation, fixing small typos, or making a small, well-scoped spec improvement (with validation).

For contribution guidelines and CLA requirements, see [CONTRIBUTING.md](CONTRIBUTING.md).

> Note: This GitHub repository is generated from an internal Meta repository. PRs are reviewed on GitHub, then imported internally by Meta maintainers. You may not see a traditional “merge commit”, but accepted changes will appear once synced. (Details in `CONTRIBUTING.md`.)

## Validating the OpenAPI spec locally

Before opening a PR that changes any `.yaml` spec, it’s recommended to run a validator/linter locally.

### Option 1: Redocly CLI (recommended)
```bash
npm install --global @redocly/cli
redocly lint business-messaging-api_v23.0.yaml
```

### Option 2: swagger-cli
```bash
npm install --global swagger-cli
swagger-cli validate business-messaging-api_v23.0.yaml
```


## License

The Meta OpenAPI Specification is MIT licensed, as found in the [LICENSE](https://github.com/facebook/openapi/blob/main/LICENSE) file.
