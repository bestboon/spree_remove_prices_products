SpreeRemovePricesProducts
=========================

Extensión de spree que permite remover los precios de los productos del catalogo y el total de una orden.

Installation
------------

Add spree_remove_prices_products to your Gemfile:

```ruby
gem 'spree_remove_prices_products'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_remove_prices_products:install
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
require 'spree_remove_prices_products/factories'
```

Copyright (c) 2014 bestBOON C.A., released under the New BSD License
