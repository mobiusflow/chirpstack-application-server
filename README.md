# DO NOT USE THIS REPO - Use mobiusflow/chirpstack-docker

# ChirpStack Application Server

![Tests](https://github.com/brocaar/chirpstack-application-server/actions/workflows/main.yml/badge.svg?branch=master)

ChirpStack Application Server is an open-source LoRaWAN Application Server, part of the
[ChirpStack](https://www.chirpstack.io/) open-source LoRaWAN Network Server stack. It is responsible
for the node "inventory" part of a LoRaWAN infrastructure, handling of received
application payloads and the downlink application payload queue. It comes
with a web-interface and API (RESTful JSON and gRPC) and supports authorization
by using JWT tokens (optional). Received payloads are published over MQTT
and payloads can be enqueued by using MQTT or the API.

## !!! ChirpStack v4 note !!!

With the release of ChirpStack v4, the source-code has been migrated to
[https://github.com/chirpstack/chirpstack/](https://github.com/chirpstack/chirpstack/).
Please refer to the [v3 to v4 migration guide](https://www.chirpstack.io/docs/v3-v4-migration.html)
for information on how to migrate your ChirpStack v3 instance.

## Architecture

![architecture](https://www.chirpstack.io/static/img/graphs/architecture.dot.png)

### Component links

* [ChirpStack Gateway Bridge](https://www.chirpstack.io/gateway-bridge/)
* [ChirpStack Network Server](https://www.chirpstack.io/network-server/)
* [ChirpStack Application Server](https://www.chirpstack.io/application-server/)

## Links

* [Downloads](https://www.chirpstack.io/application-server/overview/downloads/)
* [Docker image](https://hub.docker.com/r/chirpstack/chirpstack-application-server/)
* [Documentation & screenshots](https://www.chirpstack.io/application-server/) and [Getting started](https://www.chirpstack.io/application-server/getting-started/)
* [Building from source](https://www.chirpstack.io/application-server/community/source/)
* [Contributing](https://www.chirpstack.io/application-server/community/contribute/)
* Support
  * [Support forum](https://forum.chirpstack.io)
  * [Bug or feature requests](https://github.com/brocaar/chirpstack-application-server/issues)

## License

ChirpStack Application Server is distributed under the MIT license. See also
[LICENSE](https://github.com/brocaar/chirpstack-application-server/blob/master/LICENSE).
