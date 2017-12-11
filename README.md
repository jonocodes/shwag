# Shwag

Shwag is a command line consumer for any API using a swagger spec. And it evolves with your spec as it changes.

## Purpose

APIs change. Using swagger's code generator to create a swagger consumer is good, but it makes it hard to keep up with and ever changing API spec.

## Use

...

## How it Works

...

### Environment variables

$SHWAG_CLIENT_DIR - In case you want to store the generated client in a directory other then the current one.

$SHWAG_CLIENT_CONFIG - In case you want to store the config in a directory other then the current one.

## Requirements

* Bash 4 ?
* Curl
* Docker

### Recommended

* jq (for json output processing and because its cool)

## Installation

* Download shwag bash script to /usr/local/bin/shwag
* `chmod +x /usr/local/bin/shwag`

## TODO

Create tests with Bash 3 Docker instance and fake server endpoint.
