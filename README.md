# OpenAPI Mocker

This repository is a fork of the original [open-api-mocker](https://github.com/jormaechea/open-api-mocker) by [jormaechea](https://github.com/jormaechea).

The purpose of this fork is to incorporate specific changes and additions that were made but could not be merged into the original repository. Those changes was made for enabling [api-mock-runner](https://github.com/sngular/api-mock-runner) development.

Please note that this fork is maintained separately and may have diverged from the original project.

## Changes and Modifications

- Solve remote and circular references.
- Add support to schema format
  - https://spec.openapis.org/oas/v3.1.0#dataTypeFormat
  - https://ajv.js.org/packages/ajv-formats.html#formats

## Usage

If you want to install as dependency use:

```
npm i -g @sngular/open-api-mocker
sngular-open-api-mocker -s my-schema.json -w
sngular-open-api-mocker --help # To prompt every available setting.
```

Otherwise you can use it as an API. See [doc from original project](https://github.com/jormaechea/open-api-mocker/blob/master/docs/README.md)

## Contributing

Feel free to contribute to this fork by submitting issues or pull requests. However, keep in mind that these changes may not be merged into the original repository.

## Acknowledgements

Our heartfelt thanks go to the following individuals and entities for their support and influence on this project:

- **jormaechea** for creating **open-api-mocker** and inspiring our work.
- The broader open-source community for promoting knowledge sharing and collaboration.
