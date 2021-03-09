# headless-chrome

[![Build Status](https://travis-ci.org/fate0/headless-chrome.svg?branch=master)](https://travis-ci.org/fate0/headless-chrome)


```
$ docker pull fate0/headless-chrome
$ docker run -it --rm --cap-add=SYS_ADMIN -p9222:9222 fate0/headless-chrome

docker pull fate0/headless-chrome

docker run -it --rm --cap-add=SYS_ADMIN --entrypoint=/bin/bash -p9222:9222 fate0/headless-chrome

/usr/bin/google-chrome --disable-gpu --headless --no-sandbox --remote-debugging-address=0.0.0.0 --remote-debugging-port=9222 --user-data-dir=/data --disable-dev-shm-usage --ignore-certificate-errors --disable-xss-auditor

```
