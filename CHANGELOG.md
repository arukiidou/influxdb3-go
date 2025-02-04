## 0.5.0 [unreleased]

## 0.4.0 [2023-11-03]

### Features

1. [#45](https://github.com/InfluxCommunity/influxdb3-go/pull/45): Add structured query support

### Docs

1. [#45](https://github.com/InfluxCommunity/influxdb3-go/pull/45): Add downsampling example

## 0.3.0 [2023-10-02]

### Features

1. [#36](https://github.com/InfluxCommunity/influxdb3-go/pull/36): Add client creation from connection string
and environment variables.

### Bug Fixes

1. [#37](https://github.com/InfluxCommunity/influxdb3-go/pull/37): `runtime error` for iterating Arrow Record without rows

## 0.2.0 [2023-08-11]

### Features

1. [#30](https://github.com/InfluxCommunity/influxdb3-go/pull/30): Add custom HTTP headers support

### Breaking Changes

1. [#31](https://github.com/InfluxCommunity/influxdb3-go/pull/31): Changed package to `influxdb3`.
Renamed config types and some options.

## 0.1.0 [2023-06-09]

- initial release of new client version
- write using v2 api
- query using flightSQL
- query using influxQL
