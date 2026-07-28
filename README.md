# capability-audio-io

Atomic authority package for `audio/io`.

- imports: `#{:audio-play :audio-record}`
- effects: `#{:personal-data :sensor-read :device-write}`
- default policy: `:approval-required`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
