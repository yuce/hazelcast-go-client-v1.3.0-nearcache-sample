# Hazelcast Go Client v1.3.0 Near Cache Sample

This project contains the code sample at https://github.com/hazelcast/hazelcast-go-client/tree/previews/v1.3.0/examples/map/nearcache/json_config with the correct `go.mod` file.

It is also possible to use programmatic configuration, see: https://github.com/hazelcast/hazelcast-go-client/tree/previews/v1.3.0/examples/map/nearcache/programmatic_config

## Requirements

* Hazelcast 5.x
* Go 1.18

## Usage

Git clone this project and `cd` into it:

    $ git clone https://github.com/yuce/hazelcast-go-client-v1.3.0-nearcache-sample.git
    $ cd hazelcast-go-client-v1.3.0-nearcache-sample

Build the project with `make` or:

    $ go build -o nearcache-sample .

That creates the `nearcache-sample`.
Run that binary with a configuration file similar to `config1.json` in the root:

    ./nearcache-sample config1.json
    
## Configuration

A sample JSON configuration is provided in the `config1.json` file.
Check out the following for more configuration options:

* [Near Cache configuration](https://github.com/hazelcast/hazelcast-go-client/blob/previews/v1.3.0/nearcache/config.go)
* [General configuration](https://github.com/hazelcast/hazelcast-go-client/blob/previews/v1.3.0/config.go)

## Documentation

See: https://github.com/hazelcast/hazelcast-go-client/blob/previews/v1.3.0/proxy_map.go

## Copyright

Copyright (c) 2022, Hazelcast, Inc. All Rights Reserved.

[Apache 2 License](LICENSE).
