# FastCore Script
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rubensrocha/fastcore)
![GitHub language count](https://img.shields.io/github/languages/count/rubensrocha/fastcore)
![GitHub top language](https://img.shields.io/github/languages/top/rubensrocha/fastcore)
![GitHub issues](https://img.shields.io/github/issues/rubensrocha/fastcore)


This is a modified version of the russian FastCore script.

## Table of contents
* [Requirements](#requirements)
* [Install](#install)
* [Tasks](#tasks)
* [Contribute](#contribute)
* [Donate](#donate)
* [Resources](#resources)


## Requirements
* Apache 2.4
* Mysql 5.7
* PHP 8.0

## Install
1. Upload all files and folders to your hosting(except database.sql file)
2. Open core/config.php and edit all database and settings fields
3. Import database.sql on your phpMyAdmin

#### Default admin credentials:
 - Username: admin
 - Password: 123456

#### Payment url's (POST notifications):
- **Payeer**: /payeer.php
- **FreeKassa**: /freekassa.php

#### Payment url's (return):
- **Success**: /user/success
- **Fail**: /user/fail

## Tasks
- [x] Compatibility with PHP 8.0
- [x] Code re-indentation
- [x] Code cleanup
- [x] Bug Fixes
- [x] Added: Semantic Versioning

## Contribute
You can contribute to this project:

- [Reporting bugs](https://github.com/rubensrocha/fastcore/issues)
- [Submitting your pull-request](https://github.com/rubensrocha/fastcore/pulls)

## Resources

- FastCore Creator: [vk.com/fastcore](https://vk.com/fastcore)
