# Xrypt

.NET has a lot of crypto primitives, but not many of them work for traditional formats used on non-Windows platforms. A perfect example of this is the PEM format used by OpenSSL and other non-Windows SSL implementations. This library provides the logic decode/encode these formats.

**There is no crypto here**. The goal of Xrypt is to make .NET's existing crypto primitives and algorithms work with these other formats.

## Supported Formats

* [PEM (Privacy Enhanced Mail)(https://en.wikipedia.org/wiki/Privacy-Enhanced_Mail) format
  * [PKCS #1](https://tools.ietf.org/html/rfc8017) RSA Keys