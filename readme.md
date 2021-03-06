
[![PHP >= 7+](https://img.shields.io/badge/php-%3E%3D%207-8892BF.svg?style=flat-square)](https://php.net/)
[![Build Status](https://secure.travis-ci.org/nixsolutions/laravel-api-boilerplate.png?branch=master)](https://travis-ci.org/AlexFloppy/laravel-api-boilerplate)
[![Coverage Status](https://coveralls.io/repos/github/nixsolutions/laravel-api-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/nixsolutions/laravel-api-boilerplate?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/nixsolutions/laravel-api-boilerplate/badges/quality-score.png)](https://scrutinizer-ci.com/g/nixsolutions/laravel-api-boilerplate/?branch=master)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg?style=flat-square)](http://www.gnu.org/licenses/agpl-3.0)
[![Dependency Status](https://www.versioneye.com/user/projects/58c6d1f87a7954003a3cacfc/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/58c6d1f87a7954003a3cacfc)

##Starting project steps

1. `$ composer install`;
2. `$ ./vendor/bin/homestead make`;
3. Generate jwt secret `php artisan jwt:secret`;
4. `$ vagrant up`;
5. Under vagrant from project root `$ php artisan migrate && php artisan db:seed`.
