# AI Provider AWS Bedrock

AWS Bedrock AI models provider for the Backdrop CMS AI module.

## Installation

- Install this module using the official [Backdrop CMS instructions](https://backdropcms.org/user-guide/modules).
- **Composer Not Required**: Requests are signed and sent by the AWS Connect module (Signature Version 4 over curl). Until AWS Connect is enabled, the module falls back to the bundled AWS SDK under `vendor/`; that fallback is deprecated and will be removed in the next major release, which requires AWS Connect.

## Issues

Bugs and feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/ai_provider_aws_bedrock/issues).

## Current Maintainer

[Justin Keiser](https://github.com/keiserjb)

## Credits

- Created for Backdrop CMS by [Justin Keiser](https://github.com/keiserjb).

- Developed with AI assistance.

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
