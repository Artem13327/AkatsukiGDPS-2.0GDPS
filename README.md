GD 2.11 VULNERABILITY IS NOT FIXED HERE, DO NOT USE

But in fact, to be honest, I don’t even know, in short, it’s better not to use
# GMDprivateServer
## Geometry Dash Private Server
Basically a Geometry Dash Server Emulator

(Original files here: https://github.com/Cvolton/GMDprivateServer)

Supported version of Geometry Dash: 1.0 - 2.11 (so any version of Geometry Dash works, as of writing this [December 10, 2017])

Required version of PHP: 5.4+ (tested up to 7.1.3)

### Setup
1) Upload the files on a webserver
2) Import database.sql into a MySQL/MariaDB database
3) Edit the links in GeometryDash.exe (some are base64 encoded since 2.1, remember that)

### Credits
Private Messaging system by someguy28 (even though he needed a ton of help from me... and by a ton I mean A TON)

Base for account settings by someguy28

Using this for XOR encryption - https://github.com/sathoro/php-xor-cipher - (incl/lib/XORCipher.php)

Using this for cloud save encryption - https://github.com/defuse/php-encryption - (incl/lib/defuse-crypto.phar)

Jscolor (color picker in packCreate.php) - http://jscolor.com/

Most of the stuff in generateHash.php has been figured out by pavlukivan and Italian APK Downloader, so credits to them
