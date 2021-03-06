Supported Packages
------------------

On each commit, Circle CI automatically compiles all supported packages with GopherJS and runs their tests:

[![Circle CI](https://circleci.com/gh/gopherjs/gopherjs.svg?style=svg)](https://circleci.com/gh/gopherjs/gopherjs)

| Name            | Supported             | Comment                           |
| --------------- | --------------------- | --------------------------------- |
| archive         |                       |                                   |
| -- tar          | yes                   |                                   |
| -- zip          | yes                   |                                   |
| bufio           | yes                   |                                   |
| builtin         | yes                   |                                   |
| bytes           | yes                   |                                   |
| compress        |                       |                                   |
| -- bzip2        | yes                   |                                   |
| -- flate        | yes                   |                                   |
| -- gzip         | yes                   |                                   |
| -- lzw          | yes                   |                                   |
| -- zlib         | yes                   |                                   |
| container       |                       |                                   |
| -- heap         | yes                   |                                   |
| -- list         | yes                   |                                   |
| -- ring         | yes                   |                                   |
| crypto          |                       |                                   |
| -- aes          | yes                   |                                   |
| -- cipher       | yes                   |                                   |
| -- des          | yes                   |                                   |
| -- dsa          | yes                   |                                   |
| -- ecdsa        | yes                   |                                   |
| -- elliptic     | yes                   |                                   |
| -- hmac         | yes                   |                                   |
| -- md5          | yes                   |                                   |
| -- rand         | yes                   |                                   |
| -- rc4          | yes                   |                                   |
| -- rsa          | yes                   |                                   |
| -- sha1         | yes                   |                                   |
| -- sha256       | yes                   |                                   |
| -- sha512       | yes                   |                                   |
| -- subtle       | yes                   |                                   |
| -- tls          | no                    |                                   |
| -- x509         | yes                   |                                   |
| -- -- pkix      | yes                   |                                   |
| database        |                       |                                   |
| -- sql          | yes                   |                                   |
| -- -- driver    | yes                   |                                   |
| debug           |                       |                                   |
| -- dwarf        | yes                   |                                   |
| -- elf          | yes                   |                                   |
| -- gosym        | yes                   |                                   |
| -- macho        | yes                   |                                   |
| -- pe           | yes                   |                                   |
| encoding        |                       |                                   |
| -- ascii85      | yes                   |                                   |
| -- asn1         | yes                   |                                   |
| -- base32       | yes                   |                                   |
| -- base64       | yes                   |                                   |
| -- binary       | yes                   |                                   |
| -- csv          | yes                   |                                   |
| -- gob          | yes                   |                                   |
| -- hex          | yes                   |                                   |
| -- json         | yes                   |                                   |
| -- pem          | yes                   |                                   |
| -- xml          | yes                   |                                   |
| errors          | yes                   |                                   |
| expvar          | yes                   |                                   |
| flag            | yes                   |                                   |
| fmt             | yes                   |                                   |
| go              |                       |                                   |
| -- ast          | yes                   |                                   |
| -- build        | no                    |                                   |
| -- doc          | yes                   |                                   |
| -- format       | yes                   |                                   |
| -- parser       | yes                   |                                   |
| -- printer      | yes                   |                                   |
| -- scanner      | yes                   |                                   |
| -- token        | yes                   |                                   |
| hash            |                       |                                   |
| -- adler32      | yes                   |                                   |
| -- crc32        | yes                   |                                   |
| -- crc64        | yes                   |                                   |
| -- fnv          | yes                   |                                   |
| html            | yes                   |                                   |
| -- template     | yes                   |                                   |
| image           | yes                   |                                   |
| -- color        | yes                   |                                   |
| -- -- palette   | yes                   |                                   |
| -- draw         | yes                   |                                   |
| -- gif          | yes                   |                                   |
| -- jpeg         | yes                   |                                   |
| -- png          | yes                   |                                   |
| index           |                       |                                   |
| -- suffixarray  | yes                   |                                   |
| io              | yes                   |                                   |
| -- ioutil       | yes                   |                                   |
| log             | yes                   |                                   |
| -- syslog       | no                    |                                   |
| math            | yes                   |                                   |
| -- big          | yes                   |                                   |
| -- cmplx        | yes                   |                                   |
| -- rand         | yes                   |                                   |
| mime            | yes                   |                                   |
| -- multipart    | yes                   |                                   |
| net             | no                    |                                   |
| -- http         | partially             | emulated via XMLHttpRequest       |
| -- -- cgi       | no                    |                                   |
| -- -- cookiejar | yes                   |                                   |
| -- -- fcgi      | yes                   |                                   |
| -- -- httptest  | partially             |                                   |
| -- -- httputil  | partially             |                                   |
| -- -- pprof     | no                    |                                   |
| -- mail         | yes                   |                                   |
| -- rpc          | partially             | data structures only (no net)     |
| -- -- jsonrpc   | yes                   |                                   |
| -- smtp         | partially             | data structures only (no net)     |
| -- textproto    | yes                   |                                   |
| -- url          | yes                   |                                   |
| os              | partially             | node.js only                      |
| -- exec         | partially             | node.js only                      |
| -- signal       | partially             | node.js only                      |
| -- user         | partially             | node.js only                      |
| path            | yes                   |                                   |
| -- filepath     | yes                   |                                   |
| reflect         | yes                   |                                   |
| regexp          | yes                   |                                   |
| -- syntax       | yes                   |                                   |
| runtime         | partially             |                                   |
| -- cgo          | no                    |                                   |
| -- debug        | no                    |                                   |
| -- pprof        | no                    |                                   |
| -- race         | no                    |                                   |
| sort            | yes                   |                                   |
| strconv         | yes                   |                                   |
| strings         | yes                   |                                   |
| sync            | yes                   |                                   |
| -- atomic       | yes                   |                                   |
| syscall         | partially             | node.js only                      |
| testing         | yes                   |                                   |
| -- iotest       | yes                   |                                   |
| -- quick        | yes                   |                                   |
| text            |                       |                                   |
| -- scanner      | yes                   |                                   |
| -- tabwriter    | yes                   |                                   |
| -- template     | yes                   |                                   |
| -- -- parse     | yes                   |                                   |
| time            | yes                   | UTC and Local only (see [issue](https://github.com/gopherjs/gopherjs/issues/64)) |
| unicode         | yes                   |                                   |
| -- utf16        | yes                   |                                   |
| -- utf8         | yes                   |                                   |
| unsafe          | no                    |                                   |
