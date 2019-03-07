# World Reader Driver
[![Build Status](https://travis-ci.org/hirmeos/world_reader_driver.svg?branch=master)](https://travis-ci.org/hirmeos/world_reader_driver) [![Release](https://img.shields.io/github/release/hirmeos/world_reader_driver.svg?colorB=58839b)](https://github.com/hirmeos/world_reader_driver/releases) [![License](https://img.shields.io/github/license/hirmeos/world_reader_driver.svg?colorB=ff0000)](https://github.com/hirmeos/world_reader_driver/blob/master/LICENSE)


## Run via crontab
```
0 0 * * 0 docker run --rm --name "world_reader_driver" --env-file /path/to/config.env -v /somewhere/to/store/preprocessing:/usr/src/app/cache -v /somewhere/to/store/output:/usr/src/app/output openbookpublishers/world_reader_driver
```
