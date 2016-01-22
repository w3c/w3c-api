# W3C API

In response to demand from developers in our community wanting to interact with [W3C](http://www.w3.org/)'s data, the W3C Systems Team has developed a Web API. Through it we are making available data on Specifications, Groups, Organizations and Users.

We will be expanding what information we expose over time.

The W3C API is a read-only Web API based on the JSON format exposing only public data.

## Documentation

The W3C API is documented at [https://w3c.github.io/w3c-api/](https://w3c.github.io/w3c-api/) and the details about the different endpoints are available at [https://api.w3.org/doc](https://api.w3.org/doc).

Webhooks are documented at [https://w3c.github.io/w3c-api/webhooks](https://w3c.github.io/w3c-api/webhooks).

## Libraries

[Apiary](https://github.com/w3c/apiary) is a simple JavaScript library to leverage the W3C API.
This library is intended to be used from W3C pages: domain pages, group pages, personal pages, etc.
With Apiary, you can inject data that is retrieved using the W3C API, in a declarative way using *placeholders*.

[node-w3capi](https://github.com/w3c/node-w3capi) provides a client for the W3C API, which exposes information about things such as specifications, groups, users, etc. It follows a simple pattern in which one builds up a query, and then causes the data to be fetched.

For using the W3C API with other languages see the [list of libraries for working with JSON HAL](https://github.com/mikekelly/hal_specification/wiki/Libraries).

## Feedback and contributions

The code of this API is not public because it is highly tied to the W3C database infrastructure and would expose sensitive information. However, we welcome feedback and strongly encourage people to submit issues [here](https://github.com/w3c/w3c-api/issues).

You can also join the [W3C's IRC](http://www.w3.org/Project/IRC/) [#webapi](irc://irc.w3.org:6667/webapi) channel.

## Historical references

* [W3C Data Platform](http://w3c.github.io/w3c-api/data-platform.html)
* [Data Platform Design](http://w3c.github.io/w3c-api/data-platform-design.html)
