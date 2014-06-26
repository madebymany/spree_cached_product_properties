Cached Product Properties
============================

Provides a simple wrapper around Prodcuct Properties that allows them to be cached.
Properties are deleted from the cache on touching the product.

Introduction goes here.

Installation
------------

Add `spree_cached_product_properties` to your Gemfile:

```ruby
gem 'spree_cached_product_properties'
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_cached_product_properties/factories'
```

Copyright (c) 2014 Made by Many, released under the New BSD License