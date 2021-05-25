# Awesome Kong

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Kong Gateway and plugins. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

- [Plugins](#plugins)
    - [Response Cache](#response-cache)
    - [Transformations](#transformations)

# Plugins

## Response Cache
* [proxy-cache-globo](https://github.com/globocom/kong-plugin-proxy-cache) - A Proxy Caching plugin for Kong makes it fast and easy to configure caching of responses and serving of those cached responses in Redis. It caches responses bases on configurable response code and request headers with the request method. ![open](https://img.shields.io/badge/Kong-open%20source-brightgreen) ![DB-less compatible](https://img.shields.io/badge/DB--less-compatible-blue)

* [proxy-cache-kong](https://docs.konghq.com/hub/kong-inc/proxy-cache) - This plugin provides a reverse proxy cache implementation for Kong. It caches response entities based on configurable response code and content type, as well as request method. It can cache per-Consumer or per-API. Cache entities are stored for a configurable period of time, after which subsequent requests to the same resource will re-fetch and re-store the resource. Cache entities can also be forcefully purged via the Admin API prior to their expiration time. ![open](https://img.shields.io/badge/Kong-open%20source-brightgreen) ![DB-less compatible](https://img.shields.io/badge/DB--less-compatible-blue)

* [proxy-caching-advanced](https://docs.konghq.com/hub/kong-inc/proxy-cache-advanced) - This plugin provides a reverse proxy cache implementation for Kong. It caches response entities based on configurable response code and content type, as well as request method. It can cache per-Consumer or per-API. Cache entities are stored for a configurable period of time, after which subsequent requests to the same resource will re-fetch and re-store the resource. Cache entities can also be forcefully purged via the Admin API prior to their expiration time. ![Enterprise](https://img.shields.io/badge/Kong-enterprise-important) ![DB-less compatible](https://img.shields.io/badge/DB--less-compatible-blue)

## Transformations
* [template-transformer](https://github.com/stone-payments/kong-plugin-template-transformer) - This is a Kong middleware to transform requests / responses, using pre-configured templates. ![open](https://img.shields.io/badge/Kong-open%20source-brightgreen) ![DB-less compatible](https://img.shields.io/badge/DB--less-compatible-blue)

* [url-rewrite](https://github.com/stone-payments/kong-plugin-url-rewrite) - When using Kong, you can create routes that proxy to an upstream. The problem lies when the upstream has an url that is not very friendly to your clients, or restful, or even pretty. When you add a Route in Kong, you have a somewhat limited url rewrite capability. This plugin simply throws away the url set in Kong route and uses the url set in it’s configuration to proxy to the upstream. This gives you full freedom as to how to write your url’s in Kong and inner services as well. ![open](https://img.shields.io/badge/Kong-open%20source-brightgreen) ![DB-less compatible](https://img.shields.io/badge/DB--less-compatible-blue)

# GUI
* [konga](https://github.com/pantsel/konga) - More than just another GUI to KONG Admin API - Konga is not an official app, no affiliation with Kong. ![open](https://img.shields.io/badge/Kong-open%20source-brightgreen) ![DB-less compatible](https://img.shields.io/badge/DB--less-not%20compatible-red)
