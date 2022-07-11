# Hazelcast Go Client v1.3.0 Near Cache Sample

This project contains the code sample at https://github.com/hazelcast/hazelcast-go-client/tree/previews/v1.3.0/examples/map/nearcache/json_config with the correct `go.mod` file.

It is also possible to use programmatic configuration, see: https://github.com/hazelcast/hazelcast-go-client/tree/previews/v1.3.0/examples/map/nearcache/programmatic_config

## Requirements

* Hazelcast 5.x
* Go 1.18

## Usage

Run with a configuration file similar to `config1.json` in the root:

```
go run ./main.go config1.json
```

## Configuration

A sample JSON configuration is provided in the `config1.json` file.
See: https://github.com/hazelcast/hazelcast-go-client/blob/previews/v1.3.0/nearcache/config.go for more configuration options.

## Documentation

See: https://github.com/hazelcast/hazelcast-go-client/blob/previews/v1.3.0/proxy_map.go

## Copyright

Copyright (c) 2022, Hazelcast, Inc. All Rights Reserved.

[Apache 2 License](LICENSE).
