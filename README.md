# JRuby 9.0.0.0 + Torquebox 4 Boilerplate

This boilerplate Rack application is designed as a starting point for high-performance web applications.

It includes the web component of Torquebox 4 which is currently regarded as the [highest performance](http://www.madebymarket.com/blog/dev/ruby-web-benchmark-report.html) Ruby application server.

JRuby 9.0.0.0 has been chosen for its Ruby 2.2 support.

As these components are in pre-release state there may be some stability/performance issues.

## Installation

Ensure you have [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) installed before installing JRuby.

Install JRuby 9.0.0.0, either from the [binaries](http://www.jruby.org/download) or using a Ruby version manager (e.g. [RVM)](http://rvm.io)):

    rvm install jruby-9.0.0.0.pre1

Install the gem dependencies:

    bundle

## Running

Run the application with Torquebox 4:

    torquebox run

## Deployment to Heroku

The boilerplate has been tested on Heroku. To deploy this application to Heroku:

    heroku create
    git push heroku master
