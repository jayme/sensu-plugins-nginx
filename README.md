## Sensu-Plugins-nginx

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-nginx.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-nginx)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-nginx.svg)](http://badge.fury.io/rb/sensu-plugins-nginx)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-nginx/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-nginx)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-nginx/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-nginx)

## Functionality

### nginx-metrics
<<<<<<< HEAD
Fetch the nginx status page and convert the response into graphit metrics


## Files
 * bin/nginx-metrics.rb
=======
Get the nginx metrics from the status page url for use with Graphite


## Files
 * bin/nginx-metrics
>>>>>>> updated to 0.0.1-alpha.2

## Installation


Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install <gem> -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

`gem install sensu-plugins-nginx`

Add *sensu-plugins-nginx* to your Gemfile, manifest, cookbook, etc

## Notes
