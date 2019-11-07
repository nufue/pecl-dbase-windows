PECL dbase extension compiled for Windows
=================================

This repository contains `php_dbase` extension compiled for use on Windows.

**You are encouraged to use official PECL build of version 7.0.1 -** https://pecl.php.net/package/dbase/7.0.1/windows

PHP 7.3
--------------------
Based on pecl/dbase version [7.0.0beta1](https://pecl.php.net/package/dbase/7.0.0beta1).

Compiler version: VC15

| Architecture | x86 | x64 |
|---|---|---|
| TS (thread-safe) | [php_dbase.dll](7.3/vc15-x86/php_dbase.dll) | [php_dbase.dll](7.3/vc15-x64/php_dbase.dll) |
| NTS (non-thread-safe) | [php_dbase_nts.dll](7.3/vc15-x86/php_dbase_nts.dll) | [php_dbase_nts.dll](7.3/vc15-x64/php_dbase_nts.dll) |

PHP 7.2
--------------------
Based on pecl/dbase version [7.0.0beta1](https://pecl.php.net/package/dbase/7.0.0beta1).

Compiler version: VC15

| Architecture | x86 | x64 |
|---|---|---|
| TS (thread-safe) | [php_dbase.dll](7.2/vc15-x86/php_dbase.dll) | [php_dbase.dll](7.2/vc15-x64/php_dbase.dll) |
| NTS (non-thread-safe) | [php_dbase_nts.dll](7.2/vc15-x86/php_dbase_nts.dll) | [php_dbase_nts.dll](7.2/vc15-x64/php_dbase_nts.dll) |


PHP 7.1
--------------------
Based on pecl/dbase version [7.0.0beta1](https://pecl.php.net/package/dbase/7.0.0beta1).

Compiler version: VC14

| Architecture | x86 | x64 |
|---|---|---|
| TS (thread-safe) | [php_dbase.dll](7.1/vc14-x86/php_dbase.dll) | [php_dbase.dll](7.1/vc14-x64/php_dbase.dll) |
| NTS (non-thread-safe) | [php_dbase_nts.dll](7.1/vc14-x86/php_dbase_nts.dll) | [php_dbase_nts.dll](7.1/vc14-x64/php_dbase_nts.dll) |

Notes on compiling - commands used
-------------------
TS: `configure --disable-all --enable-cli --enable-dbase=shared`

NTS: `configure --disable-all --enable-cli --enable-dbase=shared --disable-zts`
