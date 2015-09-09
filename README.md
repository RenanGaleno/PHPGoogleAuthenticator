Google Authenticator PHP class
=====================

[![Build Status](https://api.travis-ci.org/RenanGaleno/PHPGoogleAuthenticator.svg)](https://travis-ci.org/RenanGaleno/PHPGoogleAuthenticator)

This PHP class can be used to interact with the Google Authenticator mobile app for 2-factor-authentication. This class
can generate secrets, generate codes, validate codes and present a QR-Code for scanning the secret.

For a secure installation you have to make sure that used codes cannot be reused (replay-attack).

## Usage:

See example files

    php example1.php
    Secret is: OQB6ZZGYHCPSX4AK

    Google Charts URL for the QR-Code: https://www.google.com/chart?chs=200x200&chld=M|0&cht=qr&chl=otpauth://totp/infoATphpgangsta.de%3Fsecret%3DOQB6ZZGYHCPSX4AK

    Checking Code '848634' and Secret 'OQB6ZZGYHCPSX4AK':
    OK


## Author
**Renan Galeno**
* https://renan.eng.br/
**Michael Kliewe**
* http://www.phpgangsta.de
* http://twitter.com/PHPGangsta

## License
Licensed under the BSD License.