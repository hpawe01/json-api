---
layout: page
title: Implementations
show_sidebar: true
---

The following are projects implementing JSON:API. If you'd like your project listed, [send a
pull request](https://github.com/json-api/json-api).

> Note: This specification marked 1.0 on May 29th, 2015. The implementations
below have not been verified for compliance, but a test suite is now being
assembled to vet them.

## <a href="#client-libraries" id="client-libraries" class="headerlink"></a> Client libraries

### <a href="#client-libraries-javascript" id="client-libraries-javascript" class="headerlink"></a> JavaScript

* [ember-data](https://github.com/emberjs/data) is one of the original exemplar implementations. There is now an [official adapter](https://github.com/emberjs/data/blob/main/packages/json-api/README.md) to support json-api.
  ![GitHub last commit](https://img.shields.io/github/last-commit/emberjs/data)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Femberjs%2Fdata&query=%24.archived&label=archived)
* [backbone-relational-jsonapi](https://github.com/xbill82/backbone-relational-jsonapi) is a parsing layer for Backbone.Relational. Entities specified in JSON:API are automatically parsed to be injected into Backbone.Relational relations.
  ![GitHub last commit](https://img.shields.io/github/last-commit/xbill82/backbone-relational-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fxbill82%2Fbackbone-relational-jsonapi&query=%24.archived&label=archived)
* [orbit.js](https://github.com/orbitjs/orbit.js) is a standalone library for coordinating access to data sources and keeping their contents synchronized. Orbit's Common Library includes [JSONAPISource](https://github.com/orbitjs/orbit.js/blob/master/lib/orbit-common/jsonapi-source.js) for accessing JSON:API servers. Orbit can be used independently or with Ember.js through the [ember-orbit](https://github.com/orbitjs/ember-orbit) integration library.
  ![GitHub last commit](https://img.shields.io/github/last-commit/orbitjs/orbit.js)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Forbitjs%2Forbit.js&query=%24.archived&label=archived)
* [YAYSON](https://github.com/confetti/yayson) is an isomorphic library for serializing and reading JSON:API data. Extend it to fit your models or just use it with plain objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/confetti/yayson)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fconfetti%2Fyayson&query=%24.archived&label=archived)
* [Ember JSON API Resources](https://github.com/pixelhandler/ember-jsonapi-resources) is an [Ember CLI](http://www.ember-cli.com) Addon for a lightweight solution for data persistence in an [Ember.js](http://emberjs.com) application.
  ![GitHub last commit](https://img.shields.io/github/last-commit/pixelhandler/ember-jsonapi-resources)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fpixelhandler%2Fember-jsonapi-resources&query=%24.archived&label=archived)
* [hapi-json-api](https://github.com/wraithgar/hapi-json-api) Plugin for the hapi framework; enforces Accept/Content-type rules and rewrites Boom errors to be spec compliant.
  ![GitHub last commit](https://img.shields.io/github/last-commit/wraithgar/hapi-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwraithgar%2Fhapi-json-api&query=%24.archived&label=archived)
* [jsonapi-datastore](https://github.com/beauby/jsonapi-datastore) is a lightweight standalone library for reading, serializing, and synchronizing relational JSON:API data.
  ![GitHub last commit](https://img.shields.io/github/last-commit/beauby/jsonapi-datastore)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fbeauby%2Fjsonapi-datastore&query=%24.archived&label=archived)
* [superagent-jsonapify](https://github.com/alex94puchades/superagent-jsonapify) A really lightweight (50 lines) JSON-API client addon for [superagent](https://github.com/visionmedia/superagent), the isomorphic ajax client.
  ![GitHub last commit](https://img.shields.io/github/last-commit/alex94puchades/superagent-jsonapify)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Falex94puchades%2Fsuperagent-jsonapify&query=%24.archived&label=archived)
* [angular-jsonapi](https://github.com/jakubrohleder/angular-jsonapi) An AngularJS JSON:API client
  ![GitHub last commit](https://img.shields.io/github/last-commit/jakubrohleder/angular-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjakubrohleder%2Fangular-jsonapi&query=%24.archived&label=archived)
* [redux-json-api](https://github.com/dixieio/redux-json-api) A library which integrated JSON:APIs with Redux store
  ![GitHub last commit](https://img.shields.io/github/last-commit/dixieio/redux-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdixieio%2Fredux-json-api&query=%24.archived&label=archived)
* [devour-client](https://github.com/twg/devour) A lightweight, framework agnostic, highly flexible JSON:API client
  ![GitHub last commit](https://img.shields.io/github/last-commit/twg/devour)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftwg%2Fdevour&query=%24.archived&label=archived)
* [json-api-normalizer](https://github.com/yury-dymov/json-api-normalizer) Normalizes JSON:API documents for state management solutions like Redux and Mobx
  ![GitHub last commit](https://img.shields.io/github/last-commit/yury-dymov/json-api-normalizer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fyury-dymov%2Fjson-api-normalizer&query=%24.archived&label=archived)
* [jsona](https://github.com/olosegres/jsona) Data formatter that creates customizable, simplified objects from JSON or stored reduxObject (result object of [json-api-normalizer](https://github.com/yury-dymov/json-api-normalizer)), and creates correct JSON from the same simplified objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/olosegres/jsona)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Folosegres%2Fjsona&query=%24.archived&label=archived)
* [active-resource](https://github.com/nicklandgrebe/activeresource.js) A standalone, convention-driven JavaScript ORM that maps to your JSON:API server and allows for advanced queries and relational management through a smooth interface.
  ![GitHub last commit](https://img.shields.io/github/last-commit/nicklandgrebe/activeresource.js)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnicklandgrebe%2Factiveresource.js&query=%24.archived&label=archived)
* [redux-bees](https://github.com/cantierecreativo/redux-bees) A nice, short and declarative way to interact with JSON:APIs in React+Redux
  ![GitHub last commit](https://img.shields.io/github/last-commit/cantierecreativo/redux-bees)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcantierecreativo%2Fredux-bees&query=%24.archived&label=archived)
* [Coloquent](https://github.com/DavidDuwaer/Coloquent) Javascript/Typescript library mapping objects and their interrelations to JSON:API, with a clean, fluent ActiveRecord-like (e.g. similar to Laravel's Eloquent) syntax  for creating, retrieving, updating and deleting model objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/DavidDuwaer/Coloquent)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FDavidDuwaer%2FColoquent&query=%24.archived&label=archived)
* [kitsu](https://github.com/wopian/kitsu) A simple, lightweight & framework agnostic JSON:API client
  ![GitHub last commit](https://img.shields.io/github/last-commit/wopian/kitsu)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwopian%2Fkitsu&query=%24.archived&label=archived)
* [Sarala JSON API data formatter](https://github.com/milroyfraser/sarala-json-api-data-formatter) is a simple and fluent framework agnostic javascript library to transform standard JSON:API responses to simple JSON objects and vice versa.
  ![GitHub last commit](https://img.shields.io/github/last-commit/milroyfraser/sarala-json-api-data-formatter)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmilroyfraser%2Fsarala-json-api-data-formatter&query=%24.archived&label=archived)
* [Sarala](https://github.com/milroyfraser/sarala) is a javascript package which gives you a [Laravel Eloquent](https://laravel.com/docs/5.6/eloquent) like syntax to perform CRUD operations against an JSON:API built according to [JSON:API specification](http://jsonapi.org/format/).
  ![GitHub last commit](https://img.shields.io/github/last-commit/milroyfraser/sarala)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmilroyfraser%2Fsarala&query=%24.archived&label=archived)
* [jsonapi-client](https://github.com/itsfadnis/jsonapi-client) A convenient module to consume a jsonapi service
  ![GitHub last commit](https://img.shields.io/github/last-commit/itsfadnis/jsonapi-client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fitsfadnis%2Fjsonapi-client&query=%24.archived&label=archived)
* [JSORM](https://github.com/jsonapi-suite/jsorm) is an isomorphic ActiveRecord clone that issues JSON:API requests instead of SQL and is part of the larger [JSONAPI Suite](https://github.com/jsonapi-suite/).
  ![GitHub last commit](https://img.shields.io/github/last-commit/jsonapi-suite/jsorm)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjsonapi-suite%2Fjsorm&query=%24.archived&label=archived)
* [jsonapi-vuex](https://github.com/mrichar1/jsonapi-vuex) A module for interacting with a jsonapi service using a Vuex store, restructuring/normalizing records to make life easier.
  ![GitHub last commit](https://img.shields.io/github/last-commit/mrichar1/jsonapi-vuex)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmrichar1%2Fjsonapi-vuex&query=%24.archived&label=archived)
* [heather-js](https://github.com/bitex-la/heather-js) A library for parsing JSONAPI into objects from ES6 classes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/bitex-la/heather-js)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fbitex-la%2Fheather-js&query=%24.archived&label=archived)
* [@hyral/core](https://github.com/SyneticNL/Hyral) - An advanced, documented, easily extendable and lightweight (JSON:)API abstraction library with ORM-like CRUD support, automatic relationships handling and support for multiple (different) backends.
  ![GitHub last commit](https://img.shields.io/github/last-commit/SyneticNL/Hyral)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FSyneticNL%2FHyral&query=%24.archived&label=archived)
* [@hyral/vue](https://github.com/SyneticNL/Hyral/tree/master/packages/vue) - Vue(x) integration for [@hyral/core](https://github.com/SyneticNL/Hyral) for Store-module creation and mixins
  ![GitHub last commit](https://img.shields.io/github/last-commit/SyneticNL/Hyral)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FSyneticNL%2FHyral&query=%24.archived&label=archived)
* [jsonapi-redux-data](https://github.com/wednesday-solutions/jsonapi-redux-data) - a library that makes integration of jsonapi with react + redux effortless and easy.
  ![GitHub last commit](https://img.shields.io/github/last-commit/wednesday-solutions/jsonapi-redux-data)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwednesday-solutions%2Fjsonapi-redux-data&query=%24.archived&label=archived)
* [jsonapi-fractal](https://github.com/andersondanilo/jsonapi-fractal) JSON:API Serializer inspired by Fractal (PHP)
  ![GitHub last commit](https://img.shields.io/github/last-commit/andersondanilo/jsonapi-fractal)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fandersondanilo%2Fjsonapi-fractal&query=%24.archived&label=archived)
* [ts-japi](https://github.com/jun-sheaf/ts-japi) - A zero-dependency, highly-modular, js/ts-friendly, recursible, framework-agnostic library for serializing data to the JSON:API specification. Serializes the entire specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jun-sheaf/ts-japi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjun-sheaf%2Fts-japi&query=%24.archived&label=archived)
* [mobx-async-store](https://github.com/artemis-ag/mobx-async-store) - A Mobx-based store for async data fetching and state management for the JSON:API specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/artemis-ag/mobx-async-store)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fartemis-ag%2Fmobx-async-store&query=%24.archived&label=archived)
* [spraypaint](https://github.com/graphiti-api/spraypaint.js) - JS Client for Graphiti similar to ActiveRecord. Written in Typescript but works in plain old ES5 as well. This library is isomorphic - use it from the browser, or from the server with NodeJS.
  ![GitHub last commit](https://img.shields.io/github/last-commit/graphiti-api/spraypaint.js)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fgraphiti-api%2Fspraypaint.js&query=%24.archived&label=archived)
* [json-api-models](https://github.com/tobyzerner/json-api-models) - A lightweight layer for working with JSON:API data.
  ![GitHub last commit](https://img.shields.io/github/last-commit/tobyzerner/json-api-models)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftobyzerner%2Fjson-api-models&query=%24.archived&label=archived)
* [fetchja](https://github.com/caiotarifa/fetchja) - A super simple, modern, and lightweight library for dealing with JSON:API (Kitsu-like, but using Fetch API instead of Axios).
  ![GitHub last commit](https://img.shields.io/github/last-commit/caiotarifa/fetchja)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcaiotarifa%2Ffetchja&query=%24.archived&label=archived)

### <a href="#client-libraries-typescript" id="client-libraries-typescript" class="headerlink"></a> Typescript
* [ts-angular-jsonapi](https://github.com/reyesoft/ts-angular-jsonapi) A JSON:API library developed for AngularJS in Typescript
  ![GitHub last commit](https://img.shields.io/github/last-commit/reyesoft/ts-angular-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Freyesoft%2Fts-angular-jsonapi&query=%24.archived&label=archived)
* [ngrx-json-api](https://github.com/abdulhaq-e/ngrx-json-api) A JSON:API client for Angular 2 ngrx toolset
  ![GitHub last commit](https://img.shields.io/github/last-commit/abdulhaq-e/ngrx-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fabdulhaq-e%2Fngrx-json-api&query=%24.archived&label=archived)
* [ts-jsonapi](https://github.com/mohuk/ts-jsonapi) JSON:API (De)Serializer in Typescript
  ![GitHub last commit](https://img.shields.io/github/last-commit/mohuk/ts-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmohuk%2Fts-jsonapi&query=%24.archived&label=archived)
* [ngx-jsonapi](https://github.com/reyesoft/ngx-jsonapi) A JSON:API fast client library for Angular with storage+memory cache.
  ![GitHub last commit](https://img.shields.io/github/last-commit/reyesoft/ngx-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Freyesoft%2Fngx-jsonapi&query=%24.archived&label=archived)
* [@crnk/angular-ngrx](https://www.npmjs.com/package/@crnk/angular-ngrx) Angular helper library for ngrx-json-api and (optionally) crnk. Facilitates the binding of UI components to ngrx-json-api, most notably tables and forms.
* [Grivet](https://github.com/muellerbbm-vas/grivet) A JSON:API client library written in TypeScript with emphasis on RESTful traversal of resources according to HATEOAS principles.
  ![GitHub last commit](https://img.shields.io/github/last-commit/muellerbbm-vas/grivet)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmuellerbbm-vas%2Fgrivet&query=%24.archived&label=archived)
* [DatX](https://github.com/infinum/datx) is an opinionated data store for use with the MobX state management library that adds JSON:API support with [datx-jsonapi](https://github.com/infinum/datx/tree/master/packages/datx-jsonapi) mixin.
  ![GitHub last commit](https://img.shields.io/github/last-commit/infinum/datx)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Finfinum%2Fdatx&query=%24.archived&label=archived)
* [jsonapi-fractal](https://github.com/andersondanilo/jsonapi-fractal) JSON:API Serializer inspired by Fractal (PHP)
  ![GitHub last commit](https://img.shields.io/github/last-commit/andersondanilo/jsonapi-fractal)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fandersondanilo%2Fjsonapi-fractal&query=%24.archived&label=archived)
* [ts-japi](https://github.com/jun-sheaf/ts-japi) - A zero-dependency, highly-modular, js/ts-friendly, recursible, framework-agnostic library for serializing data to the JSON:API specification. Serializes the entire specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jun-sheaf/ts-japi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjun-sheaf%2Fts-japi&query=%24.archived&label=archived)
* [drupal-jsonapi-params](https://github.com/d34dman/drupal-jsonapi-params) A library for building query parameters when connecting with Drupal CMS's JSON:API.
  ![GitHub last commit](https://img.shields.io/github/last-commit/d34dman/drupal-jsonapi-params)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fd34dman%2Fdrupal-jsonapi-params&query=%24.archived&label=archived)
* [EntityStore.TS](https://github.com/dipscope/EntityStore.TS) - ORM like abstraction layer for TypeScript which includes extensible [provider](https://github.com/dipscope/JsonApiEntityProvider.TS) for accessing JSON:API servers.
  ![GitHub last commit](https://img.shields.io/github/last-commit/dipscope/EntityStore.TS)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdipscope%2FEntityStore.TS&query=%24.archived&label=archived)

### <a href="#client-libraries-ios" id="client-libraries-ios" class="headerlink"></a> iOS

* [jsonapi-ios](https://github.com/joshdholtz/jsonapi-ios) is a library for loading data from a JSON:API datasource. Parses JSON:API data into models with support for auto-linking of resources and custom model classes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/joshdholtz/jsonapi-ios)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjoshdholtz%2Fjsonapi-ios&query=%24.archived&label=archived)
* [Spine](https://github.com/wvteijlingen/spine) is a Swift library for working with JSON:API APIs. It supports mapping to custom model classes, fetching, advanced querying, linking and persisting.
  ![GitHub last commit](https://img.shields.io/github/last-commit/wvteijlingen/spine)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwvteijlingen%2Fspine&query=%24.archived&label=archived)
* [Vox](https://github.com/aronbalog/Vox) is a Swift JSON:API client framework with custom model classes support and nice networking interface.
  ![GitHub last commit](https://img.shields.io/github/last-commit/aronbalog/Vox)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Faronbalog%2FVox&query=%24.archived&label=archived)
* [Japx](https://github.com/infinum/Japx) is lightweight JSON:API parser that flattens complex JSON:API structure and turns it into simple JSON and vice versa. It works by transferring Dictionary to Dictionary, so you can use Codable, Unbox, Wrap, ObjectMapper or any other object mapping tool that you prefer. It supports Objective-C as well.
  ![GitHub last commit](https://img.shields.io/github/last-commit/infinum/Japx)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Finfinum%2FJapx&query=%24.archived&label=archived)
* [mattpolzin / JSONAPI](https://github.com/mattpolzin/JSONAPI) is a Swift Codable library with heavy emphasis on type-safety. It is platform agnostic so it can be used client- and server-side.
  ![GitHub last commit](https://img.shields.io/github/last-commit/mattpolzin/JSONAPI)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmattpolzin%2FJSONAPI&query=%24.archived&label=archived)
* [IzzyParser](https://github.com/undabot/izzyparser-ios) is a lightweight library for serializing and deserializing JSON:API objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/undabot/izzyparser-ios)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fundabot%2Fizzyparser-ios&query=%24.archived&label=archived)
* [Datadog/swift-jsonapi](https://github.com/Datadog/swift-jsonapi) is a Swift library that provides macros to simplify the encoding and decoding of JSON:API responses.
  ![GitHub last commit](https://img.shields.io/github/last-commit/Datadog/swift-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FDatadog%2Fswift-jsonapi&query=%24.archived&label=archived)

### <a href="#client-libraries-ruby" id="client-libraries-ruby" class="headerlink"></a> Ruby

* [jsonapi-consumer](https://github.com/jsmestad/jsonapi-consumer) a ruby library for consuming JSONAPI payloads.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jsmestad/jsonapi-consumer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjsmestad%2Fjsonapi-consumer&query=%24.archived&label=archived)
* [JsonApiClient](https://github.com/chingor13/json_api_client) attempts to give you a query building framework that is easy to understand (similar to ActiveRecord scopes).
  ![GitHub last commit](https://img.shields.io/github/last-commit/chingor13/json_api_client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fchingor13%2Fjson_api_client&query=%24.archived&label=archived)
* [Munson](https://github.com/coryodaniel/munson) is a ruby JSONAPI client that can act as an ORM or integrate with your models via fine-grained agnosticism. Easy to configure and customize. Includes a chainable/customizable query builder, attributes API and dirty tracking.
  ![GitHub last commit](https://img.shields.io/github/last-commit/coryodaniel/munson)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcoryodaniel%2Fmunson&query=%24.archived&label=archived)
* [json-api-vanilla](https://github.com/trainline/json-api-vanilla) a reference-aware ruby library for JSONAPI deserialization that doesn't require setting up classes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/trainline/json-api-vanilla)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftrainline%2Fjson-api-vanilla&query=%24.archived&label=archived)
* [SimpleJSONAPIClient](https://github.com/amcaplan/simple_jsonapi_client) gives you lower-level control for API operations, while your models and their relationships maintain a neat, ActiveRecord-inspired interface.
  ![GitHub last commit](https://img.shields.io/github/last-commit/amcaplan/simple_jsonapi_client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Famcaplan%2Fsimple_jsonapi_client&query=%24.archived&label=archived)
* [jsonapi-unwrapper](https://github.com/Sonberg/jsonapi-unwrapper) a simple and lightweight library to deserialize JSON:API payloads.
  ![GitHub last commit](https://img.shields.io/github/last-commit/Sonberg/jsonapi-unwrapper)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FSonberg%2Fjsonapi-unwrapper&query=%24.archived&label=archived)

### <a href="#client-libraries-php" id="client-libraries-php" class="headerlink"></a> PHP

* [Art4 / json-api-client](https://github.com/Art4/json-api-client) is a library for validating and handling the response body in a simple OOP way.
  ![GitHub last commit](https://img.shields.io/github/last-commit/Art4/json-api-client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FArt4%2Fjson-api-client&query=%24.archived&label=archived)
* [woohoolabs / yang](https://github.com/woohoolabs/yang) is a PSR-7 compatible library that is able to build and send requests, and handle responses.
  ![GitHub last commit](https://img.shields.io/github/last-commit/woohoolabs/yang)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwoohoolabs%2Fyang&query=%24.archived&label=archived)
* [enm/json-api-client](https://eosnewmedia.github.io/JSON-API-Client/) is an abstract client-side PHP implementation of the json:api specification which is based on [enm/json-api-common](https://eosnewmedia.github.io/JSON-API-Common/). It allows you to send json:api requests via your own http client implementation or via a buzz or guzzle client.
* [floor9design-ltd/json-api-formatter](https://github.com/floor9design-ltd/json-api-formatter) An open source library designed to be used for generating and interacting with (making and receiving) JSON API requests. 100% unit tested and actively maintained by the author. Easy to use with frameworks such as Laravel/Symfony. 
  ![GitHub last commit](https://img.shields.io/github/last-commit/floor9design-ltd/json-api-formatter)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ffloor9design-ltd%2Fjson-api-formatter&query=%24.archived&label=archived)
* [swisnl/json-api-client](https://github.com/swisnl/json-api-client) Is a package for mapping remote {json:api} resources to Eloquent like models and collections.
  ![GitHub last commit](https://img.shields.io/github/last-commit/swisnl/json-api-client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fswisnl%2Fjson-api-client&query=%24.archived&label=archived)

### <a href="#client-libraries-dart" id="client-libraries-dart" class="headerlink"></a> Dart

* [json_api](https://pub.dev/packages/json_api) is a full-fledged client for Flutter/Web/VM.
* [rest_data](https://pub.dev/packages/rest_data) is a REST API client based on `ember-data` concepts which includes a JSON:API adapter.
* [jsonapi_client](https://pub.dev/packages/jsonapi_client) is a simple JSON:API v1.0 client written in Dart.
* [japx](https://pub.dev/packages/japx) is a lightweight JSON:API parser that flattens complex JSON:API structure and turns it into simple JSON and vice versa

### <a href="#client-libraries-perl" id="client-libraries-perl" class="headerlink"></a> Perl

* [PONAPI::Client](https://metacpan.org/pod/PONAPI::Client) is a simple/extensible JSON:API v1.0 client.

### <a href="#client-libraries-java" id="client-libraries-java" class="headerlink"></a> Java

* [jsonapi-converter](https://github.com/jasminb/jsonapi-converter) is a Java JSON:API v1.0 client. Besides providing means for serialisation/deserialisation, client comes with Retrofit plugin.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jasminb/jsonapi-converter)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjasminb%2Fjsonapi-converter&query=%24.archived&label=archived)
* [crnk.io](https://github.com/crnk-project/crnk-framework) is a JSON:API framework for clients and servers. On the client-side it targets both Java and Android development. As for the backend side a rich set of modules helps with the integration of various Java frameworks.  
  ![GitHub last commit](https://img.shields.io/github/last-commit/crnk-project/crnk-framework)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcrnk-project%2Fcrnk-framework&query=%24.archived&label=archived)
 * [jsonapi](https://github.com/MarkoMilos/jsonapi) Library for streamlined use of JSON:API using Kotlin and Java built on top of Moshi from Square. It is built with a powerful api and supports JVM (Java/Kotlin) and Android. Supporting deserialization and serialization it is meant to be used on both client and server side.
   ![GitHub last commit](https://img.shields.io/github/last-commit/MarkoMilos/jsonapi)
   ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FMarkoMilos%2Fjsonapi&query=%24.archived&label=archived)

### <a href="#client-libraries-android" id="client-libraries-android" class="headerlink"></a> Android
* [faogustavo/JSONApi](https://github.com/faogustavo/JSONApi) library for deserializing automatic. It can be integrated with retrofit. It has some ideas from Morpheus and jsonapi-converter but has some aditionals.
  ![GitHub last commit](https://img.shields.io/github/last-commit/faogustavo/JSONApi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ffaogustavo%2FJSONApi&query=%24.archived&label=archived)
* [moshi-jsonapi](https://github.com/kamikat/moshi-jsonapi) serialize/deserialize JSON:API v1.0 using fantistic Moshi API! With friendly Java interface and easy integration with Retrofit.
  ![GitHub last commit](https://img.shields.io/github/last-commit/kamikat/moshi-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fkamikat%2Fmoshi-jsonapi&query=%24.archived&label=archived)
* [Morpheus](https://github.com/xamoom/Morpheus) library for deserializing your resources with automatic mapping for relationships. Uses gson to map objects in attributes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/xamoom/Morpheus)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fxamoom%2FMorpheus&query=%24.archived&label=archived)
* [Izzy JSONAPI parser](https://github.com/undabot/izzy-json-api-android) library for deserializing and serializing resources with support both for Gson and Jackson parsers. It also has simple Retrofit integration.
  ![GitHub last commit](https://img.shields.io/github/last-commit/undabot/izzy-json-api-android)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fundabot%2Fizzy-json-api-android&query=%24.archived&label=archived)
* [JsonApiX](https://github.com/infinum/kotlin-jsonapix) annotation processor library for serializing and deserializing Kotlin classes. It's easy to use - setup only requires annotating classes. Retrofit integration is included.
  ![GitHub last commit](https://img.shields.io/github/last-commit/infinum/kotlin-jsonapix)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Finfinum%2Fkotlin-jsonapix&query=%24.archived&label=archived)

### <a href="#client-libraries-r" id="client-libraries-r" class="headerlink"></a> R

* [rjsonapi](https://github.com/sckott/rjsonapi) is an R client to consume JSONAPI's.
  ![GitHub last commit](https://img.shields.io/github/last-commit/sckott/rjsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fsckott%2Frjsonapi&query=%24.archived&label=archived)

### <a href="#client-libraries-elm" id="client-libraries-elm" class="headerlink"></a> Elm

* [elm-jsonapi](https://github.com/noahzgordon/elm-jsonapi) provides decoders and helper functions for clients receiving JSON:API payloads.
  ![GitHub last commit](https://img.shields.io/github/last-commit/noahzgordon/elm-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnoahzgordon%2Felm-jsonapi&query=%24.archived&label=archived)
* [elm-jsonapi-http](https://github.com/noahzgordon/elm-jsonapi-http) wraps `elm-jsonapi` and handles the details of content negotiation with JSON:API-compliant servers, providing a smoother interface for consumers.
  ![GitHub last commit](https://img.shields.io/github/last-commit/noahzgordon/elm-jsonapi-http)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnoahzgordon%2Felm-jsonapi-http&query=%24.archived&label=archived)

### <a href="#client-libraries-net" id="client-libraries-net" class="headerlink"></a> .NET

* [Hypermedia.JsonApi.Client](https://github.com/cosullivan/Hypermedia/) is a set of extension methods to the HttpClient which allow for reading and writing of JSON:API documents.
  ![GitHub last commit](https://img.shields.io/github/last-commit/cosullivan/Hypermedia)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcosullivan%2FHypermedia&query=%24.archived&label=archived)
* [JsonApiSerializer](https://github.com/codecutout/JsonApiSerializer) is a configurationless JSON:API serialization and deserialization library implemented as a Json.NET `JsonSerializerSetting`. It leverages the existing power and flexibility of Json.NET while providing a sensible default mapping between JSON:API and CLR objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/codecutout/JsonApiSerializer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcodecutout%2FJsonApiSerializer&query=%24.archived&label=archived)
* [JsonApiFramework.Client](https://github.com/scott-mcdonald/JsonApiFramework) is a *portable* .NET Standard/Core client-side framework where developers define the domain model of the resources of a hypermedia API server either through configuration and/or conventions called a *service model*. With a *service model* developers can use a *document context* that represents a session with a JSON:API compound *document* for reading or writing of various JSON:API abstractions such as resources, resource identifiers, relationships, links, meta information, error objects, and version information all serialized/deserialized as high level CLR objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/scott-mcdonald/JsonApiFramework)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fscott-mcdonald%2FJsonApiFramework&query=%24.archived&label=archived)
* [FSharp.JsonApi](https://github.com/cmeeren/FSharp.JsonApi/) is a library that allows you to use F# to easily create and consume flexible, strongly typed web APIs following the JSON:API specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/cmeeren/FSharp.JsonApi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcmeeren%2FFSharp.JsonApi&query=%24.archived&label=archived)
* [jsonapi-consumer](https://github.com/OKTAYKIR/jsonapi-consumer/) is a simple client-side .NET Standard wrapper framework for consuming JSON:API based APIs.
  ![GitHub last commit](https://img.shields.io/github/last-commit/OKTAYKIR/jsonapi-consumer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FOKTAYKIR%2Fjsonapi-consumer&query=%24.archived&label=archived)

### <a href="#client-libraries-python" id="client-libraries-python" class="headerlink"></a> Python

* [jsonapi-requests](https://github.com/socialwifi/jsonapi-requests/) Simple and fun high-level JSONAPI client for Python. Contains ORM which makes consuming the API even easier, in a DRY manner. It has a low-level API similar to requests as well, which gives you all the flexibility that you may need.
  ![GitHub last commit](https://img.shields.io/github/last-commit/socialwifi/jsonapi-requests)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fsocialwifi%2Fjsonapi-requests&query=%24.archived&label=archived)
* [jsonapi-client](https://github.com/qvantel/jsonapi-client) Comprehensive yet easy-to-use, pythonic, ORM-like access to JSON:API services
  ![GitHub last commit](https://img.shields.io/github/last-commit/qvantel/jsonapi-client)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fqvantel%2Fjsonapi-client&query=%24.archived&label=archived)
* [json-api-doc](https://github.com/noplay/json-api-doc) JSON:API parser returning a simple Python dictionary
  ![GitHub last commit](https://img.shields.io/github/last-commit/noplay/json-api-doc)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnoplay%2Fjson-api-doc&query=%24.archived&label=archived)
* [json-api-smart](https://github.com/NilssonPL/json-api-smart) JSON:API with an ORM interface
  ![GitHub last commit](https://img.shields.io/github/last-commit/NilssonPL/json-api-smart)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FNilssonPL%2Fjson-api-smart&query=%24.archived&label=archived)

## <a href="#server-libraries" id="server-libraries" class="headerlink"></a> Server libraries

### <a href="#server-libraries-swift" id="server-libraries-swift" class="headerlink"></a> Swift
* [aonawale / JSONAPISerializer](https://github.com/aonawale/JSONAPISerializer) is a server side swift framework agnostic library that implements JSON:API v1.0.
  ![GitHub last commit](https://img.shields.io/github/last-commit/aonawale/JSONAPISerializer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Faonawale%2FJSONAPISerializer&query=%24.archived&label=archived)
* [mattpolzin / JSONAPI](https://github.com/mattpolzin/JSONAPI) is a Swift Codable library with heavy emphasis on type-safety. It is platform agnostic so it can be used client- and server-side.
  ![GitHub last commit](https://img.shields.io/github/last-commit/mattpolzin/JSONAPI)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmattpolzin%2FJSONAPI&query=%24.archived&label=archived)
* [Datadog/swift-jsonapi](https://github.com/Datadog/swift-jsonapi) is a Swift library that provides macros to simplify the encoding and decoding of JSON:API responses.
  ![GitHub last commit](https://img.shields.io/github/last-commit/Datadog/swift-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FDatadog%2Fswift-jsonapi&query=%24.archived&label=archived)

### <a href="#server-libraries-php" id="server-libraries-php" class="headerlink"></a> PHP

* [tobyz / json-api-server](https://github.com/tobyzerner/json-api-server) is a framework-agnostic declarative JSON:API server implementation.
  ![GitHub last commit](https://img.shields.io/github/last-commit/tobyzerner/json-api-server)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftobyzerner%2Fjson-api-server&query=%24.archived&label=archived)
* [neomerx / json-api](https://github.com/neomerx/json-api) is a framework agnostic library that fully implements JSON:API v1.0.
  ![GitHub last commit](https://img.shields.io/github/last-commit/neomerx/json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fneomerx%2Fjson-api&query=%24.archived&label=archived)
* [limoncello-php / app](https://github.com/limoncello-php/app) is a JSON:API v1.0 quick start server application for [neomerx / json-api](https://github.com/neomerx/json-api).
  ![GitHub last commit](https://img.shields.io/github/last-commit/limoncello-php/app)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Flimoncello-php%2Fapp&query=%24.archived&label=archived)
* [lode / jsonapi](https://github.com/lode/jsonapi) is a human-friendly library to implement JSON:API v1.1 without needing to know the specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/lode/jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Flode%2Fjsonapi&query=%24.archived&label=archived)
* [woohoolabs / yin](https://github.com/woohoolabs/yin) is a library for advanced users aiming for efficiency and elegance.
  ![GitHub last commit](https://img.shields.io/github/last-commit/woohoolabs/yin)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fwoohoolabs%2Fyin&query=%24.archived&label=archived)
* [nilportugues / json-api](https://github.com/nilportugues/json-api) Serializer transformers outputting valid API responses in JSON and JSON:API formats.
  ![GitHub last commit](https://img.shields.io/github/last-commit/nilportugues/json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnilportugues%2Fjson-api&query=%24.archived&label=archived)
* [nilportugues / symfony2-jsonapi-transformer](https://github.com/nilportugues/symfony2-jsonapi-transformer) Symfony 2 JSON:API Transformer Bundle outputting valid API responses in JSON and JSON:API formats.
  ![GitHub last commit](https://img.shields.io/github/last-commit/nilportugues/symfony2-jsonapi-transformer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnilportugues%2Fsymfony2-jsonapi-transformer&query=%24.archived&label=archived)
* [nilportugues / laravel5-jsonapi-transformer](https://github.com/nilportugues/laravel5-jsonapi-transformer) Laravel 5 JSON:API Transformer Package outputting valid API responses in JSON and JSON:API formats.
  ![GitHub last commit](https://img.shields.io/github/last-commit/nilportugues/laravel5-jsonapi-transformer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnilportugues%2Flaravel5-jsonapi-transformer&query=%24.archived&label=archived)
* [tuyakhov / yii2-json-api](https://github.com/tuyakhov/yii2-json-api) Implementation of JSON:API specification for the Yii framework.
  ![GitHub last commit](https://img.shields.io/github/last-commit/tuyakhov/yii2-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftuyakhov%2Fyii2-json-api&query=%24.archived&label=archived)
* [json-api-php/json-api](https://github.com/json-api-php/json-api) An attempt to translate the JSON:API specification into a set of high quality unit/functional tests and implement it in PHP 7 strictly following TDD and SOLID OOP principles.
  ![GitHub last commit](https://img.shields.io/github/last-commit/json-api-php/json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjson-api-php%2Fjson-api&query=%24.archived&label=archived)
* [laravel-json-api/laravel](https://github.com/laravel-json-api/laravel) Laravel implementation of the JSON:API specification, with full feature support and extensive documentation.
  ![GitHub last commit](https://img.shields.io/github/last-commit/laravel-json-api/laravel)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Flaravel-json-api%2Flaravel&query=%24.archived&label=archived)
* [FriendsOfCake/crud-json-api](https://github.com/FriendsOfCake/crud-json-api) CakePHP Crud Listener for building maintainable JSON:API compliant APIs.
  ![GitHub last commit](https://img.shields.io/github/last-commit/FriendsOfCake/crud-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FFriendsOfCake%2Fcrud-json-api&query=%24.archived&label=archived)
* [thephpleague/fractal](http://fractal.thephpleague.com/) A partial implementation of the JSON:API spec allowing for an easy drop in JSON rendering solution.
* [oligus/jad](https://github.com/oligus/jad) A library that turns doctrine entities into json:api resource, or collection of resources, automagically.
  ![GitHub last commit](https://img.shields.io/github/last-commit/oligus/jad)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Foligus%2Fjad&query=%24.archived&label=archived)
* [enm/json-api-server](https://eosnewmedia.github.io/JSON-API-Server/) is an abstract server-side PHP (>= 7.2) implementation of the json:api specification, based on [enm/json-api-common](https://eosnewmedia.github.io/JSON-API-Common/). It handles json:api requests via request handlers through a centralized handle-method. It can be used with psr-7-request/response or your own request and response logic.
* [enm/json-api-server-bundle](https://eosnewmedia.github.io/JSON-API-Server-Bundle/) is a symfony bundle which integrates [enm/json-api-server](https://eosnewmedia.github.io/JSON-API-Server/) into your symfony application (symfony version ^4.0).
* [raml-json-api](https://github.com/RJAPI/raml-json-api) RAML based JSON:API code generator for Laravel. Generates controllers, middlewares, models, routes, migrations and serves JSON:API.
  ![GitHub last commit](https://img.shields.io/github/last-commit/RJAPI/raml-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FRJAPI%2Framl-json-api&query=%24.archived&label=archived)
* [paknahad/jsonapi-bundle](https://github.com/paknahad/jsonapi-bundle) is a Symfony bundle. It is the fastest way to generate API.
  ![GitHub last commit](https://img.shields.io/github/last-commit/paknahad/jsonapi-bundle)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fpaknahad%2Fjsonapi-bundle&query=%24.archived&label=archived)
* [swisnl/json-api-server](https://github.com/swisnl/json-api-server) is a Laravel package to get a JSON:API up and running in minutes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/swisnl/json-api-server)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fswisnl%2Fjson-api-server&query=%24.archived&label=archived)
* [hackerboy/json-api](https://github.com/hackerboydotcom/json-api) is a lightweight library that helps you to implement JSONAPI easily
  ![GitHub last commit](https://img.shields.io/github/last-commit/hackerboydotcom/json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fhackerboydotcom%2Fjson-api&query=%24.archived&label=archived)
* [drupal](https://www.drupal.org/project/drupal) The Drupal CMS supports exposing all data it manages (entities) according to the JSON:API specification. [jsonapi_extras](https://www.drupal.org/project/jsonapi_extras) is an optional extra module to change resource type names, field names and more.
* [bednic/json-api](https://gitlab.com/bednic/json-api) Annotation driven library for creating valid JSON API response document from your objects.
* [pz/doctrine-rest](https://github.com/R3VoLuT1OneR/doctrine-rest) library provides basic tools for implementation of JSON:API with Doctrine 2
  ![GitHub last commit](https://img.shields.io/github/last-commit/R3VoLuT1OneR/doctrine-rest)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FR3VoLuT1OneR%2Fdoctrine-rest&query=%24.archived&label=archived)
* [pz/jsonapi-resource](https://github.com/R3VoLuT1OneR/jsonapi-resource) Serialize PHP class object into JSON:API resource object using PHP 8.0 Attributes.
  ![GitHub last commit](https://img.shields.io/github/last-commit/R3VoLuT1OneR/jsonapi-resource)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FR3VoLuT1OneR%2Fjsonapi-resource&query=%24.archived&label=archived)
* [binarcode/laravel-restify](https://github.com/binarcode/laravel-restify) The fastest way to make a powerful JSON:API compatible Rest API with Laravel [Reference Docs](https://restify.binarcode.com/).
  ![GitHub last commit](https://img.shields.io/github/last-commit/binarcode/laravel-restify)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fbinarcode%2Flaravel-restify&query=%24.archived&label=archived)
* [API Platform](https://api-platform.com) is an API-first Framework supporting JSON:API. 

### <a href="#server-libraries-node-js" id="server-libraries-node-js" class="headerlink"></a> Node.js
* [Fortune.js](http://fortune.js.org/) is a library that includes a [comprehensive implementation of JSON:API](https://github.com/fortunejs/fortune-json-api).
  ![GitHub last commit](https://img.shields.io/github/last-commit/fortunejs/fortune-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ffortunejs%2Ffortune-json-api&query=%24.archived&label=archived)
* [json-api](https://www.npmjs.org/package/json-api) turns an Express + Mongoose app into a JSON-API server.
* [endpoints](https://github.com/endpoints) is an implementation of JSON:API using [Bookshelf](http://bookshelfjs.org).
* [YAYSON](https://github.com/confetti/yayson) is an isomorphic library for serializing and reading JSON:API data. Simply use it with plain objects or extend it to fit your ORM (currently it has an adapter for [Sequelize](http://sequelizejs.com)).
  ![GitHub last commit](https://img.shields.io/github/last-commit/confetti/yayson)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fconfetti%2Fyayson&query=%24.archived&label=archived)
* [jsonapi-serializer](https://github.com/SeyZ/jsonapi-serializer) is a Node.js framework agnostic library for serializing your data to JSON:API.
  ![GitHub last commit](https://img.shields.io/github/last-commit/SeyZ/jsonapi-serializer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FSeyZ%2Fjsonapi-serializer&query=%24.archived&label=archived)
* [jsonapi-server](https://github.com/holidayextras/jsonapi-server) A feature-rich config-driven json:api framework.
  ![GitHub last commit](https://img.shields.io/github/last-commit/holidayextras/jsonapi-server)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fholidayextras%2Fjsonapi-server&query=%24.archived&label=archived)
  * [jsonapi-store-memoryhandler](https://github.com/holidayextras/jsonapi-server/blob/master/documentation/resources.md) An in-memory data store for rapid prototyping.
    ![GitHub last commit](https://img.shields.io/github/last-commit/holidayextras/jsonapi-server)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fholidayextras%2Fjsonapi-server&query=%24.archived&label=archived)
  * [jsonapi-store-relationaldb](https://github.com/holidayextras/jsonapi-store-relationaldb) A relational database handler for jsonapi-server.
    ![GitHub last commit](https://img.shields.io/github/last-commit/holidayextras/jsonapi-store-relationaldb)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fholidayextras%2Fjsonapi-store-relationaldb&query=%24.archived&label=archived)
  * [jsonapi-store-mongodb](https://github.com/holidayextras/jsonapi-store-mongodb) A mongodb handler for jsonapi-server.
    ![GitHub last commit](https://img.shields.io/github/last-commit/holidayextras/jsonapi-store-mongodb)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fholidayextras%2Fjsonapi-store-mongodb&query=%24.archived&label=archived)
  * [jsonapi-store-elasticsearch](https://github.com/holidayextras/jsonapi-store-elasticsearch) An elasticsearch handler for jsonapi-server.
    ![GitHub last commit](https://img.shields.io/github/last-commit/holidayextras/jsonapi-store-elasticsearch)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fholidayextras%2Fjsonapi-store-elasticsearch&query=%24.archived&label=archived)
* [jagql](https://jagql.github.io) A resource driven framework to set up a {json:api} + GraphQL endpoint in record time.
  * [jagql/store-sequelize](https://npmjs.com/@jagql/store-sequelize) persist jagql resources to Postgres/MySQL/MSSQL/SQLite
* [loopback-component-jsonapi](https://github.com/digitalsadhu/loopback-component-jsonapi) JSON:API support for [loopback](https://github.com/strongloop/loopback) highly-extensible, open-source Node.js framework
  ![GitHub last commit](https://img.shields.io/github/last-commit/digitalsadhu/loopback-component-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdigitalsadhu%2Floopback-component-jsonapi&query=%24.archived&label=archived)
* [loopback-jsonapi-model-serializer](https://www.npmjs.com/package/loopback-jsonapi-model-serializer) JSON:API serializer for loopback models.
* [jsonapi-mapper](https://github.com/scoutforpets/jsonapi-mapper) JSON:API-Compliant Serialization for your Node ORM.
  ![GitHub last commit](https://img.shields.io/github/last-commit/scoutforpets/jsonapi-mapper)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fscoutforpets%2Fjsonapi-mapper&query=%24.archived&label=archived)
* [jaysonapi](https://github.com/digia/jaysonapi) jaysonapi is a framework agnostic JSON:API v1.0.0 serializer. jaysonapi provides more of a functional approach to serializing your data. Define a serializer with a type and schema, and call serialize on it passing in the data, included, meta, errors, etc. as a plain object.
  ![GitHub last commit](https://img.shields.io/github/last-commit/digia/jaysonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdigia%2Fjaysonapi&query=%24.archived&label=archived)
* [json-api-ify](https://github.com/kutlerskaggs/json-api-ify) serialize the **** out of your data. json:api v1.0 complaint.
  ![GitHub last commit](https://img.shields.io/github/last-commit/kutlerskaggs/json-api-ify)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fkutlerskaggs%2Fjson-api-ify&query=%24.archived&label=archived)
* [bookshelf-jsonapi-params](https://github.com/scoutforpets/bookshelf-jsonapi-params) automatically apply JSON:API filtering, pagination, sparse fieldsets, includes, and sorting to your Bookshelf.js queries.
  ![GitHub last commit](https://img.shields.io/github/last-commit/scoutforpets/bookshelf-jsonapi-params)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fscoutforpets%2Fbookshelf-jsonapi-params&query=%24.archived&label=archived)
* [Lux](https://github.com/postlight/lux) is a MVC style Node.js framework for building lightning fast JSON:APIs.
  ![GitHub last commit](https://img.shields.io/github/last-commit/postlight/lux)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fpostlight%2Flux&query=%24.archived&label=archived)
* [jsonapi-mock](https://github.com/Thomas-X/jsonapi-mock) A [json-server](https://github.com/typicode/json-server) inspired jsonapi mock server. Setup a jsonapi mock server in almost no time, uses lowdb.
  ![GitHub last commit](https://img.shields.io/github/last-commit/Thomas-X/jsonapi-mock)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FThomas-X%2Fjsonapi-mock&query=%24.archived&label=archived)
* [DenaliJS](http://denalijs.org) A layered-conventions framework for building ambitious APIs. Includes a powerful addon system, best-in-class developer experience, and extensive documentation.
* [jsonapi-fractal](https://github.com/andersondanilo/jsonapi-fractal) JSON:API Serializer inspired by Fractal (PHP)
  ![GitHub last commit](https://img.shields.io/github/last-commit/andersondanilo/jsonapi-fractal)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fandersondanilo%2Fjsonapi-fractal&query=%24.archived&label=archived)
* [ts-japi](https://github.com/jun-sheaf/ts-japi) - A zero-dependency, highly-modular, js/ts-friendly, recursible, framework-agnostic library for serializing data to the JSON:API specification. Serializes the entire specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jun-sheaf/ts-japi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjun-sheaf%2Fts-japi&query=%24.archived&label=archived)
* [Kurier](https://github.com/kurierjs/kurier) is a TypeScript framework to create APIs following the [1.1 Spec of JSON:API](https://jsonapi.org/format/1.1/) + the [Operations proposal spec](https://github.com/json-api/json-api/blob/999e6df77b28549d6c37b163b73c8e9102400020/_format/1.1/index.md#operations).
  ![GitHub last commit](https://img.shields.io/github/last-commit/kurierjs/kurier)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fkurierjs%2Fkurier&query=%24.archived&label=archived)
* [nestjs-json-api](https://github.com/klerick/nestjs-json-api) A module for NestJS and TypeORM to implement JSON API supporting features such as, end point, query params, body params, validation and transformation response.
  ![GitHub last commit](https://img.shields.io/github/last-commit/klerick/nestjs-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fklerick%2Fnestjs-json-api&query=%24.archived&label=archived)

### <a href="#server-libraries-ruby" id="server-libraries-ruby" class="headerlink"></a> Ruby

* Plain Ruby
  * [Yaks](https://github.com/plexus/yaks) Library for building hypermedia APIs, contains a JSON:API output format.
    ![GitHub last commit](https://img.shields.io/github/last-commit/plexus/yaks)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fplexus%2Fyaks&query=%24.archived&label=archived)
  * [JSONAPI::Serializers](https://github.com/fotinakis/jsonapi-serializers) provides a pure Ruby, readonly serializer implementation.
    ![GitHub last commit](https://img.shields.io/github/last-commit/fotinakis/jsonapi-serializers)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ffotinakis%2Fjsonapi-serializers&query=%24.archived&label=archived)
  * [JSONAPI::Realizer](https://github.com/krainboltgreene/jsonapi-realizer) provides a pure Ruby pattern for turning JSON:API requests into models (has active record support and rails instructions)
    ![GitHub last commit](https://img.shields.io/github/last-commit/krainboltgreene/jsonapi-realizer)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fkrainboltgreene%2Fjsonapi-realizer&query=%24.archived&label=archived)
  * [Roar](https://github.com/apotonick/roar) Renders and parses representations of Ruby objects
    ![GitHub last commit](https://img.shields.io/github/last-commit/apotonick/roar)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fapotonick%2Froar&query=%24.archived&label=archived)
  * [Jbuilder::JsonAPI](https://github.com/vladfaust/jbuilder-json_api) Simple & lightweight extension for Jbuilder
    ![GitHub last commit](https://img.shields.io/github/last-commit/vladfaust/jbuilder-json_api)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fvladfaust%2Fjbuilder-json_api&query=%24.archived&label=archived)
  * [jsonapi-rb](http://jsonapi-rb.org) Ruby library for efficiently building and consuming JSON:API documents - with Rails and Hanami integrations.
  * [fast_jsonapi](https://github.com/Netflix/fast_jsonapi) A lightning fast JSON:API serializer for Ruby Objects.
    ![GitHub last commit](https://img.shields.io/github/last-commit/Netflix/fast_jsonapi)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FNetflix%2Ffast_jsonapi&query=%24.archived&label=archived)
  * [jsonapi_parameters](https://github.com/visualitypl/jsonapi_parameters) Rails-way to consume JSON:API input.
    ![GitHub last commit](https://img.shields.io/github/last-commit/visualitypl/jsonapi_parameters)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fvisualitypl%2Fjsonapi_parameters&query=%24.archived&label=archived)

* Ruby on Rails
  * [Jsonapi-for-rails](https://github.com/doga/jsonapi_for_rails)
    ![GitHub last commit](https://img.shields.io/github/last-commit/doga/jsonapi_for_rails)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdoga%2Fjsonapi_for_rails&query=%24.archived&label=archived)
empowers your JSONAPI compliant [Rails](http://rubyonrails.org/) APIs. Implement your APIs with very little coding.
  * [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers)
    ![GitHub last commit](https://img.shields.io/github/last-commit/rails-api/active_model_serializers)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Frails-api%2Factive_model_serializers&query=%24.archived&label=archived)
is one of the original exemplar implementations, but is slightly out of date at
the moment.
  * [JSONAPI::Resources](https://github.com/cerebris/jsonapi-resources) provides a complete framework for developing a JSON:API server. It is designed to work with Rails, and provides routes, controllers, and serializers.
    ![GitHub last commit](https://img.shields.io/github/last-commit/cerebris/jsonapi-resources)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcerebris%2Fjsonapi-resources&query=%24.archived&label=archived)
  * [JSONAPI::Utils](https://github.com/b2beauty/jsonapi-utils) works on top of [JSONAPI::Resources](https://github.com/cerebris/jsonapi-resources) taking advantage of its resource-driven style and bringing a Rails way to build modern APIs with no or less learning curve.
    ![GitHub last commit](https://img.shields.io/github/last-commit/b2beauty/jsonapi-utils)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fb2beauty%2Fjsonapi-utils&query=%24.archived&label=archived)
  * [Caprese](https://github.com/nicklandgrebe/caprese) An opinionated Rails library for creating JSON:API servers that lets you focus on customizing the behavior of your endpoints rather than the dirty work of setting them up. Leverages the power of [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers).
    ![GitHub last commit](https://img.shields.io/github/last-commit/nicklandgrebe/caprese)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fnicklandgrebe%2Fcaprese&query=%24.archived&label=archived)
  * [JSONAPI Suite](https://github.com/jsonapi-suite) facilitates a server capable of deep querying and nested writes. Works with any ORM or datastore; comes with integration test helpers and automatic swagger documentation.
  * [JSONAPI.rb](https://github.com/stas/jsonapi.rb#usage) A set of pluggable mixins providing support for serialization (using `fast_jsonapi`), error handling, includes, sparse fields, pagination, filtering (using `ransack`) and sorting. Strives to implement as much of the JSONAPI spec as possible. Small codebase (~500 sloc), good documentation and test coverage.
    ![GitHub last commit](https://img.shields.io/github/last-commit/stas/jsonapi.rb)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fstas%2Fjsonapi.rb&query=%24.archived&label=archived)
  * [Graphiti](https://www.graphiti.dev/guides/) a ruby library for RESTful Resources based on JSON:API. Works with vanilla Ruby, Sinatra and Rails.

* Sinatra
  * [Sinja](https://github.com/mwpastore/sinja) extends [Sinatra](http://www.sinatrarb.com) and leverages [JSONAPI::Serializers](https://github.com/fotinakis/jsonapi-serializers) to enable rapid development of comprehensive, read-and-write, and JSON:API v1.0-compliant web services using the DAL/ORM of your choice. It includes a simple role-based authorization scheme, support for client-generated IDs, patchless clients, and coalesced find requests, exception handling, and more.
    ![GitHub last commit](https://img.shields.io/github/last-commit/mwpastore/sinja)
    ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmwpastore%2Fsinja&query=%24.archived&label=archived)

### <a href="#server-libraries-python" id="server-libraries-python" class="headerlink"></a> Python

* [Hyp](https://github.com/kalasjocke/hyp) is a library for creating json-api responses.
  ![GitHub last commit](https://img.shields.io/github/last-commit/kalasjocke/hyp)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fkalasjocke%2Fhyp&query=%24.archived&label=archived)
* [SQLAlchemy-JSONAPI](https://github.com/coltonprovias/sqlalchemy-jsonapi) provides JSON:API serialization for SQLAlchemy models.
  ![GitHub last commit](https://img.shields.io/github/last-commit/coltonprovias/sqlalchemy-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcoltonprovias%2Fsqlalchemy-jsonapi&query=%24.archived&label=archived)
* [django-rest-framework-json-api](https://github.com/django-json-api/django-rest-framework-json-api) provides JSON:API parsing and rendering for the Django REST Framework
  ![GitHub last commit](https://img.shields.io/github/last-commit/django-json-api/django-rest-framework-json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdjango-json-api%2Fdjango-rest-framework-json-api&query=%24.archived&label=archived)
* [jsoongia](https://github.com/digia/jsoongia) is a framework agnostic JSON:API implementation.
  ![GitHub last commit](https://img.shields.io/github/last-commit/digia/jsoongia)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdigia%2Fjsoongia&query=%24.archived&label=archived)
* [ripozo](https://github.com/vertical-knowledge/ripozo/) provides a framework for serving JSON:API content (among other Hypermedia formats) in Flask, Django and more.
  ![GitHub last commit](https://img.shields.io/github/last-commit/vertical-knowledge/ripozo)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fvertical-knowledge%2Fripozo&query=%24.archived&label=archived)
* [marshmallow-jsonapi](https://github.com/marshmallow-code/marshmallow-jsonapi) provides JSON:API data formatting for any Python web framework.
  ![GitHub last commit](https://img.shields.io/github/last-commit/marshmallow-code/marshmallow-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmarshmallow-code%2Fmarshmallow-jsonapi&query=%24.archived&label=archived)
* [neoapi](https://pypi.python.org/pypi/neoapi/) serializes JSON:API–compliant responses from neomodel StructuredNodes for Neo4j data
* [xamoom-janus](https://github.com/xamoom/xamoom-janus) is a Python module to easily and fast extend Python web frameworks like Flask or BottlyPy with json:api functionality. Also offers a flexible mechanism for data mapping and hooks to intercept and extend its functionality according to your projects needs.
  ![GitHub last commit](https://img.shields.io/github/last-commit/xamoom/xamoom-janus)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fxamoom%2Fxamoom-janus&query=%24.archived&label=archived)
* [pyramid-jsonapi](https://github.com/colinhiggs/pyramid-jsonapi) Auto-build a JSON:API from sqlalchemy models using the pyramid framework.
  ![GitHub last commit](https://img.shields.io/github/last-commit/colinhiggs/pyramid-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcolinhiggs%2Fpyramid-jsonapi&query=%24.archived&label=archived)
* [Flask-REST-JSONAPI](https://github.com/miLibris/flask-rest-jsonapi) Flask extension to create web api according to jsonapi specification with Flask, Marshmallow and data provider of your choice (SQLAlchemy, MongoDB, ...)
  ![GitHub last commit](https://img.shields.io/github/last-commit/miLibris/flask-rest-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FmiLibris%2Fflask-rest-jsonapi&query=%24.archived&label=archived)
* [Flump](https://github.com/rolepoint/flump) Database agnostic JSON:API builder which depends on Flask and Marshmallow.
  ![GitHub last commit](https://img.shields.io/github/last-commit/rolepoint/flump)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Frolepoint%2Fflump&query=%24.archived&label=archived)
* [SAFRS JSON API Framework](https://github.com/thomaxxl/safrs) Flask-SQLAlchemy jsonapi implementation with auto-generated openapi (fka swagger) interface.
  ![GitHub last commit](https://img.shields.io/github/last-commit/thomaxxl/safrs)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fthomaxxl%2Fsafrs&query=%24.archived&label=archived)
* [pydantic-jsonapi](https://github.com/DeanWay/pydantic-jsonapi) JSON:api validation with python type hinting using [pydantic](https://pydantic-docs.helpmanual.io/)
  ![GitHub last commit](https://img.shields.io/github/last-commit/DeanWay/pydantic-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FDeanWay%2Fpydantic-jsonapi&query=%24.archived&label=archived)
* [pydanja](https://github.com/Centurix/pydanja) JSON:API implementation for [pydantic](https://pydantic-docs.helpmanual.io/) and [FastAPI](https://fastapi.tiangolo.com/) using generic types, complete with helpers for simplifying OpenAPI docs
  ![GitHub last commit](https://img.shields.io/github/last-commit/Centurix/pydanja)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FCenturix%2Fpydanja&query=%24.archived&label=archived)
* [Flask-Restless-NG](https://github.com/mrevutskyi/flask-restless-ng) Builds JSON:API from SQLAlchemy models using Flask
  ![GitHub last commit](https://img.shields.io/github/last-commit/mrevutskyi/flask-restless-ng)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmrevutskyi%2Fflask-restless-ng&query=%24.archived&label=archived)
* [starlette-jsonapi](https://github.com/vladmunteanu/starlette-jsonapi) Microframework on top of Starlette and marshmallow-jsonapi with support for asynchronous ORMs
  ![GitHub last commit](https://img.shields.io/github/last-commit/vladmunteanu/starlette-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fvladmunteanu%2Fstarlette-jsonapi&query=%24.archived&label=archived)
* [kt.jsonapi](https://pypi.org/project/kt.jsonapi/) JSON:API response generation using the Zope Component Architecture.
* [Flask-COMBO-JSONAPI](https://github.com/AdCombo/flask-combo-jsonapi) JSON:API flask extension for building REST APIs.
  ![GitHub last commit](https://img.shields.io/github/last-commit/AdCombo/flask-combo-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FAdCombo%2Fflask-combo-jsonapi&query=%24.archived&label=archived)
* [FastAPI-JSONAPI](https://github.com/mts-ai/FastAPI-JSONAPI) FastAPI-JSONAPI is a FastAPI extension for building REST APIs
  ![GitHub last commit](https://img.shields.io/github/last-commit/mts-ai/FastAPI-JSONAPI)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmts-ai%2FFastAPI-JSONAPI&query=%24.archived&label=archived)

### <a href="#server-libraries-go" id="server-libraries-go" class="headerlink"></a> Go

* [api2go](https://github.com/manyminds/api2go) is a full-fledged library to make it simple to provide a JSON:API with your Golang project.
  ![GitHub last commit](https://img.shields.io/github/last-commit/manyminds/api2go)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmanyminds%2Fapi2go&query=%24.archived&label=archived)
* [jsonapi](https://github.com/google/jsonapi) serializes and deserializes jsonapi formatted payloads using struct tags to annotate the structs that you already have in your Golang project. [Godoc](http://godoc.org/github.com/google/jsonapi)
  ![GitHub last commit](https://img.shields.io/github/last-commit/google/jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fgoogle%2Fjsonapi&query=%24.archived&label=archived)
* [go-json-spec-handler](https://github.com/derekdowling/go-json-spec-handler) drop-in library for handling requests and sending responses in an existing API.
  ![GitHub last commit](https://img.shields.io/github/last-commit/derekdowling/go-json-spec-handler)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fderekdowling%2Fgo-json-spec-handler&query=%24.archived&label=archived)
* [jsh-api](https://github.com/derekdowling/go-json-spec-handler/tree/master/jsh-api) deals with the dirty work of building JSON:API resource endpoints. Built on top of [jsh](https://github.com/derekdowling/go-json-spec-handler)
  ![GitHub last commit](https://img.shields.io/github/last-commit/derekdowling/go-json-spec-handler)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fderekdowling%2Fgo-json-spec-handler&query=%24.archived&label=archived)
* [mfcochauxlaberge/jsonapi](https://github.com/mfcochauxlaberge/jsonapi) offers a large set of tools to build a JSON:API compliant service.
  ![GitHub last commit](https://img.shields.io/github/last-commit/mfcochauxlaberge/jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmfcochauxlaberge%2Fjsonapi&query=%24.archived&label=archived)
* [pieoneers/jsonapi-go](https://github.com/pieoneers/jsonapi-go) lightweight JSON API implementation in Go. Make your client and server applications JSON API-enabled in hours not months.
  ![GitHub last commit](https://img.shields.io/github/last-commit/pieoneers/jsonapi-go)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fpieoneers%2Fjsonapi-go&query=%24.archived&label=archived)

### <a href="#server-libraries-net" id="server-libraries-net" class="headerlink"></a> .NET

* [JsonApiDotNetCore](https://github.com/json-api-dotnet/JsonApiDotNetCore) is a framework for building json:api compliant REST APIs using .NET Core and Entity Framework Core. It eliminates as much boilerplate as possible by offering out-of-the-box features such as sorting, filtering and pagination. You just need to focus on defining the resources and implementing your custom business logic.
  ![GitHub last commit](https://img.shields.io/github/last-commit/json-api-dotnet/JsonApiDotNetCore)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjson-api-dotnet%2FJsonApiDotNetCore&query=%24.archived&label=archived)
* [JsonApiNet](https://github.com/l8nite/JsonApiNet) lets you quickly deserialize JSON:API documents into C# entities. Supports compound documents, complex type mapping from attributes, attribute mapping, and more. [See the README](https://github.com/l8nite/JsonApiNet/blob/master/README.md) for full details.
  ![GitHub last commit](https://img.shields.io/github/last-commit/l8nite/JsonApiNet)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fl8nite%2FJsonApiNet&query=%24.archived&label=archived)
* [NJsonApi](https://github.com/jacek-gorgon/NJsonApi) is a .NET server implementation of the standard. It aims at good extensibility and performance while maintaining developer-friendliness with interchangeable conventions and builder-style configuration.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jacek-gorgon/NJsonApi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjacek-gorgon%2FNJsonApi&query=%24.archived&label=archived)
* [Migrap.AspNetCore.Hateoas](https://github.com/dcomartin/Migrap.AspNetCore.Hateoas) HATEOAS (Hypermedia as the Engine of Application State) framework for ASP.NET Core. Current implementation(s): Siren, JsonApi.
  ![GitHub last commit](https://img.shields.io/github/last-commit/dcomartin/Migrap.AspNetCore.Hateoas)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdcomartin%2FMigrap.AspNetCore.Hateoas&query=%24.archived&label=archived)
* [Saule](https://github.com/joukevandermaas/saule/) is a small JSON:API 1.0 compatible library that integrates well with established Web API conventions. It has complete documentation and near 100% test coverage.
  ![GitHub last commit](https://img.shields.io/github/last-commit/joukevandermaas/saule)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjoukevandermaas%2Fsaule&query=%24.archived&label=archived)
* [Hypermedia.JsonApi.WebApi](https://github.com/cosullivan/Hypermedia/) is a Web API media type formatter for reading and writing JSON:API. It supports an external resource model definition and natively
  ![GitHub last commit](https://img.shields.io/github/last-commit/cosullivan/Hypermedia)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcosullivan%2FHypermedia&query=%24.archived&label=archived)
includes related resources.
* [JsonApiSerializer](https://github.com/codecutout/JsonApiSerializer) is a configurationless JSON:API serialization and deserialization library implemented as a Json.NET `JsonSerializerSetting`. It leverages the existing power and flexibility of Json.NET while providing a sensible default mapping between JSON:API and CLR objects.
  ![GitHub last commit](https://img.shields.io/github/last-commit/codecutout/JsonApiSerializer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcodecutout%2FJsonApiSerializer&query=%24.archived&label=archived)
* [JsonApiFramework.Server](https://github.com/scott-mcdonald/JsonApiFramework) is a *portable* .NET Standard/Core server-side framework where developers define the domain model of the resources of a hypermedia API server either through configuration and/or conventions called a *service model*. With a *service model* developers can use a *document context* that represents a session with a JSON:API compound *document* for reading or writing of various JSON:API abstractions such as resources, resource identifiers, relationships, links, meta information, error objects, and version information all serialized/deserialized as high level CLR objects with automatic generation of JSON:API hypermedia.
  ![GitHub last commit](https://img.shields.io/github/last-commit/scott-mcdonald/JsonApiFramework)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fscott-mcdonald%2FJsonApiFramework&query=%24.archived&label=archived)
* [FSharp.JsonApi](https://github.com/cmeeren/FSharp.JsonApi/) is a library that allows you to use F# to easily create and consume flexible, strongly typed web APIs following the JSON:API specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/cmeeren/FSharp.JsonApi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcmeeren%2FFSharp.JsonApi&query=%24.archived&label=archived)
* [Felicity](https://github.com/cmeeren/Felicity/) is a boilerplate-free JSON:API framework for your functional F# domain model, optimized for developer happiness
  ![GitHub last commit](https://img.shields.io/github/last-commit/cmeeren/Felicity)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fcmeeren%2FFelicity&query=%24.archived&label=archived)

### <a href="#server-libraries-java" id="server-libraries-java" class="headerlink"></a> Java

* [crnk.io](http://www.crnk.io) is a JSON:API framework for clients and servers. It was started as a fork for Katharsis after the later [lost development momentum](https://www.reddit.com/r/java/comments/6hs0n8/crnkio_10_released_crank_up_rest_development/). It has similar concepts but with active development support. On the server-side it comes, among others,
  with a rich set of integrations (Servlet, JAX-RS, Spring, JPA, Bean Validation, Zipkin and more), bulk updates with JSON Patch,  a meta-model for automation purposes, client stub generation for TypeScript and a module API for third-party contributions.
* [Elide](http://elide.io) is a web framework supporting JSON:API. Through annotation-based JSON:API endpoint generation, Elide enables you to focus on your data model, security model, and business logic while avoiding unnecessary boilerplate. Moreover, through use of the JSON:API Patch extension, [Elide](http://elide.io) provides full support for database transactions.
* [JSON:API for Spring HATEOAS](https://github.com/toedter/spring-hateoas-jsonapi) provides serialization/deserialization of the Spring HATEOAS representation models. The project also provides a builder to easily create relationships, included resource objects, pagination, and more.
  ![GitHub last commit](https://img.shields.io/github/last-commit/toedter/spring-hateoas-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftoedter%2Fspring-hateoas-jsonapi&query=%24.archived&label=archived)
* [jsonapi-rvp](https://github.com/xlate/jsonapi-rvp) utilizes the platform capabilities available in the Jakarta EE environment (formerly Java EE) to expose JPA entities via JSON:API. Features include query and entity validation (using Bean Validators), pagination, use of surrogate keys as record identifiers, support for LEFT outer join conditions, and a simple JavaScript client.
  ![GitHub last commit](https://img.shields.io/github/last-commit/xlate/jsonapi-rvp)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fxlate%2Fjsonapi-rvp&query=%24.archived&label=archived)
* [JSON:API object converter](https://github.com/MieskeB/json-api-spring-boot) converts normal Java objects to JSON:API standard with the use of annotations in the viewmodels (dtos).
  ![GitHub last commit](https://img.shields.io/github/last-commit/MieskeB/json-api-spring-boot)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FMieskeB%2Fjson-api-spring-boot&query=%24.archived&label=archived)
* [Dashjoin Low Code Development Platform](https://github.com/dashjoin/platform) connects to relational, document, and graph databases and makes them available via JSON:API. The platform offers powerful access control mechanisms, a query editor, and graphical layout designers.
  ![GitHub last commit](https://img.shields.io/github/last-commit/dashjoin/platform)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdashjoin%2Fplatform&query=%24.archived&label=archived)
* [jsonapi-simple](https://github.com/devslm/jsonapi-simple) is a simple implementation of the JSON:API specification (only required output fields). This library implements only top-level fields: data, links, errors and meta (using spring boot dependencies) without any relationships, includes and others. It implemented also filtering, sorting and sparse fieldset. [See the documentation](https://devslm.github.io/jsonapi-simple/) for full details.
  ![GitHub last commit](https://img.shields.io/github/last-commit/devslm/jsonapi-simple)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fdevslm%2Fjsonapi-simple&query=%24.archived&label=archived)

### <a href="#server-libraries-scala" id="server-libraries-scala" class="headerlink"></a> Scala
* [scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) A Scala library for producing JSON output (and deserializing JSON input) based on JSON:API specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/scala-jsonapi/scala-jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fscala-jsonapi%2Fscala-jsonapi&query=%24.archived&label=archived)

### <a href="#server-libraries-elixir" id="server-libraries-elixir" class="headerlink"></a> Elixir

* [ja_serializer](https://github.com/AgilionApps/ja_serializer) is a behaviour and DSL to emit conforming JSON. Suitable for use in a Phoenix view or in a Plug stack.
  ![GitHub last commit](https://img.shields.io/github/last-commit/AgilionApps/ja_serializer)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2FAgilionApps%2Fja_serializer&query=%24.archived&label=archived)
* [jsonapi](https://github.com/jeregrine/jsonapi) is a serializer and query parser built with plain old functions. Can parse and validate a JSONAPI compliant query and serialize Ecto Models or Elixir Structs into conforming JSON. Suitable for use in a Phoenix view, Plug Stack or anywhere you can call functions.
  ![GitHub last commit](https://img.shields.io/github/last-commit/jeregrine/jsonapi)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fjeregrine%2Fjsonapi&query=%24.archived&label=archived)

### <a href="#server-libraries-haskell" id="server-libraries-haskell" class="headerlink"></a> Haskell

* [json-api](https://github.com/toddmohney/json-api) functions and datatypes for representing user-defined resources in accordance with the JSON-API specification.
  ![GitHub last commit](https://img.shields.io/github/last-commit/toddmohney/json-api)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftoddmohney%2Fjson-api&query=%24.archived&label=archived)

### <a href="#server-libraries-perl" id="server-libraries-perl" class="headerlink"></a> Perl

* [PONAPI::Server](https://metacpan.org/pod/PONAPI::Server) is a Plack-based web server, providing a generic service adhering to the spec. just plug your data-repository & play.

### <a href="#server-libraries-vala" id="server-libraries-vala" class="headerlink"></a> Vala

* [JSON-API-GLib](https://github.com/major-lab/json-api-glib) provides GObjects that can be serialized to and unserialized from payloads with [JSON-GLib](https://wiki.gnome.org/Projects/JsonGlib).
  ![GitHub last commit](https://img.shields.io/github/last-commit/major-lab/json-api-glib)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmajor-lab%2Fjson-api-glib&query=%24.archived&label=archived)

### <a href="#server-libraries-rust" id="server-libraries-rust" class="headerlink"></a> Rust

* [jsonapi-rust](https://github.com/michiel/jsonapi-rust) A Rust library for serializing, deserializing and working with JSON-API data
  ![GitHub last commit](https://img.shields.io/github/last-commit/michiel/jsonapi-rust)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmichiel%2Fjsonapi-rust&query=%24.archived&label=archived)

### <a href="#server-libraries-dart" id="server-libraries-dart" class="headerlink"></a> Dart

* [json_api_server](https://pub.dartlang.org/packages/json_api_server) is a JSON:API server running on Dart VM.

### <a href="#server-libraries-crystal" id="server-libraries-crystal" class="headerlink"></a> Crystal

* [jsonapi-serializer-cr](https://github.com/andersondanilo/jsonapi-serializer-cr) is a JSON:API Serializer for Crystal Lang.
  ![GitHub last commit](https://img.shields.io/github/last-commit/andersondanilo/jsonapi-serializer-cr)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fandersondanilo%2Fjsonapi-serializer-cr&query=%24.archived&label=archived)

## <a href="#examples" id="examples" class="headerlink"></a> Examples

* [Endpoints provides a fully working example API](http://github.com/endpoints/example/)
  ![GitHub last commit](https://img.shields.io/github/last-commit/endpoints/example)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fendpoints%2Fexample&query=%24.archived&label=archived)
* [Sinja provides a fully-working example API](https://github.com/mwpastore/sinja/tree/master/demo-app)
  ![GitHub last commit](https://img.shields.io/github/last-commit/mwpastore/sinja)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fmwpastore%2Fsinja&query=%24.archived&label=archived)

## <a href="#related-tools" id="related-tools" class="headerlink"></a> Related Tools

### <a href="#related-tools-playground" id="related-tools-playground" class="headerlink"></a> Playground

* [json-api-document-viewer](https://tadast.github.io/json-api-document-viewer) the flat json:api structure is a good way to express complex relationships between objects. However the same flatness makes it difficult for humans to "parse" these relationships. This tool visualises object relationships by visually nesting them.
* [corroborate](http://corroborate.arenpatel.com/) JSON:API request/response payload validator. It warns when there is a specification violation and also informs when a recommendation has not been followed.

### <a href="#related-tools-ruby" id="related-tools-ruby" class="headerlink"></a> Ruby

* [json-patch](https://github.com/guillec/json-patch) implementation of JSON Patch (rfc6902)
  ![GitHub last commit](https://img.shields.io/github/last-commit/guillec/json-patch)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Fguillec%2Fjson-patch&query=%24.archived&label=archived)
* [hana](https://github.com/tenderlove/hana) implementation of the JSON Patch and JSON pointer spec
  ![GitHub last commit](https://img.shields.io/github/last-commit/tenderlove/hana)
  ![Archived](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Frepos%2Ftenderlove%2Fhana&query=%24.archived&label=archived)

### <a href="#related-tools-javascript" id="related-tools-javascript" class="headerlink"></a> JavaScript

* [json-api-merge](https://www.npmjs.com/package/json-api-merge) JSON:API specific redundant duplication algorithm for merging included resources into original data
* [json-patch](https://www.npmjs.org/package/json-patch) implementation of JSON Patch (rfc6902)

### <a href="#server-python" id="server-python" class="headerlink"></a> Python

* [jsonpatch](https://python-json-patch.readthedocs.org) implementation of JSON Patch (rfc6902)
* [drf-json-patch](https://drf-json-patch.readthedocs.org) integrates jsonpatch with Django REST Framework
