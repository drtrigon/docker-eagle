[![Build Status](https://travis-ci.org/drtrigon/docker-eagle.svg?branch=master)](https://travis-ci.org/drtrigon/docker-eagle)

https://github.com/drtrigon/test-eagle-edrc

https://github.com/pywikibot-catfiles/docker-file-metadata

https://github.com/drtrigon/sketchbook

(https://github.com/drtrigon/eagle)


## TODO
# TODO: gerber jobs do not finish properly yet - compare output to test-eagle-edrc travis output

# TODO: testing without "|| true" to get error feadback, add other eagle versions
# TODO: may be create scripts for eagle commands and add them in dockerfile

# TODO: drc&erc but how to get output?'
# TODO: auto-router step with proposal for routing as output

* TODO: add support for other EagleCAD IDE versions

## Examples
https://github.com/drtrigon/docker-eagle/blob/master/.travis.yml

Results going to: https://github.com/drtrigon/test-eagle-edrc/tree/result/travis

## Setup
Overload Origin with Both Remotes in order to clone and set this repo up use:
```
$ git clone file://///data/mount/gvfs/smb-share:server=.../01git/docker-eagle.git
$ cd docker-eagle
$ git remote set-url --add origin https://github.com/drtrigon/docker-eagle.git
```
you can check the settings with:
```
$ git remote -v
origin  /data/mount/gvfs/smb-share:server=.../01git/docker-eagle.git/ (fetch)
origin  /data/mount/gvfs/smb-share:server=.../01git/docker-eagle.git/ (push)
origin  https://github.com/drtrigon/docker-eagle.git (push)
```
(needs one single pull/push only)
