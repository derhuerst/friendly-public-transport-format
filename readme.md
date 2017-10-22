# Friendly Public Transport Format (FPTF)

This repo outlines **a format for APIs, libraries and datasets containing and working with public transport data.** See [the spec](docs/readme.md) and the [list of JS modules](modules.md).

![CC-licensed](https://img.shields.io/github/license/public-transport/friendly-public-transport-format.svg)
[![chat on gitter](https://badges.gitter.im/public-transport/Lobby.svg)](https://gitter.im/public-transport/Lobby)

It tries to keep things simple:

- JSON and [ndjson](http://ndjson.org) only
- a flat, intuitive representation of public transport timetables & infrastructure
- conceptually inspired by the de-facto standard [GTFS](https://developers.google.com/transit/gtfs/)

Specifically, it trades

- efficiency for consumability: GTFS sets feel like database dumps.
- completeness for ease-of-use: Only basic attributes are required, most is optional.

Things still missing:

- concise definitions
- clear naming & recommendations for optional data


## Contributing

We are looking forward to discuss & extend this format further! If you have a question or want to propose changes, go to [the issues page](https://github.com/public-transport/friendly-public-transport-format/issues). Keep our [contributing guidelines in mind](contributing.md).
