[![Build Status](https://travis-ci.org/jedisct1/iptoasn-webservice.svg?branch=master)](https://travis-ci.org/jedisct1/iptoasn-webservice)

# iptoasn-webservice

Webservice to map IP addresses to AS information.

This is the source code of the public API from [iptoasn.com](https://iptoasn.com).

Requires [rust](https://www.rust-lang.org/).

# Default URL:
[http:localhost:53661/v1/as/ip/](http:localhost:53661/v1/as/ip/)

# Usage:

```sh
$ curl -H'Accept: application/json' https://api.iptoasn.com/v1/as/ip/<ip address>
```
```json
{
  "announced": true,
  "as_country_code": "US",
  "as_description": "LEVEL3 - Level 3 Communications, Inc.",
  "as_number": 3356,
  "first_ip": "4.0.0.0",
  "ip": "4.3.2.1",
  "last_ip": "4.23.87.255"
}
```
