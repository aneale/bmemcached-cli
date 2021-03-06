# bmemcached-cli #
> Version: 0.1.0

bmemcached-cli is a simple python wrapper for python-binary-memcached. This is a hack of [memcache-cli](https://github.com/andrewgross/memcache-cli) by Andrew W. Gross, motivated by the need to have a Memcached command line interface that supports SASL (binary protocol).

## Installing
Download the source and run the following command in the directory:
```console
pip install . -r requirements.pip
```

## Using
To connect to a Memcached bucket using plaintext protocol:
```console
bmemcached-cli host:port [host:port]
```
To connect to a SASL-enabled Memcached bucket:
```console
bmemcached-cli username:password@host:port [host:port]
```

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/444ac886fef2c00bbe2b1272bd3505f3 "githalytics.com")](http://githalytics.com/RedisLabs/bmemcached-cli)
