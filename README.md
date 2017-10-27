SimpleAES
=========

[![Build Status](https://travis-ci.org/jonjomckay/dotnet-simpleaes.svg)](https://travis-ci.org/jonjo/dotnet-simpleaes)

This library is a straight-up transliteration of [Simple-AES256](https://github.com/ChazSII/Simple-AES256) from VB 
to C# for ease of use inside .NET Core applications.

## Usage

### Encrypting

To encrypt, simply call `SimpleAES.AES256.Encrypt(textToEncrypt, key)` and it will return you a Base64-encoded value that contains the salt, IV and cipher text.

### Decrypting

To decrypt, call `SimpleAES.AES256.Decrypt(encryptedContent, key)` and the original string value will be returned.

## Contributing

Contributions are welcome to the project - whether they are feature requests, improvements or bug fixes! Refer to
[CONTRIBUTING.md](CONTRIBUTING.md) for our contribution requirements.

## License

This library is released under the [MIT License](http://opensource.org/licenses/mit-license.php). It includes code
ported from the [Simple-AES256](https://github.com/ChazSII/Simple-AES256) project, which is also released under the
[MIT License](https://opensource.org/licenses/MIT).
