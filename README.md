# Impact Platform: Memcached
[Docker](https://www.docker.com/) container for [Memcached](https://memcached.org/).

## Overview
Cache all the things.

## Docker-Compose Usage
```
memcached:
    image: impactbot/impact-platform-memcached
    ports:
        - "11211:11211"
    environment:
        - MEMCACHED_PASSWORD=somesecretpassword
```

* Username: `admin`
* Password: provide with environment variable `MEMCACHED_PASSWORD`
