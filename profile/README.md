# Squasher

AI-native observability. Know why production broke. Then squash it.

Squasher collects errors, logs, traces, and session replays and links them to one issue. An agent
reads that data, names the likely cause, and links the events and spans it used. Connect GitHub
and it can open a fix pull request for you to review. It does not merge.

## Install

Node.js, Next.js, browser, and edge apps:

```sh
npm install @squasher-ai/node    # or nextjs, browser, edge
```

Go apps only (Go 1.21 or later), from the folder with `go.mod`:

```sh
go get github.com/squasher-ai/squasher-go
```

Other languages send OpenTelemetry (OTLP) with no Squasher SDK. See the
[quickstart](https://docs.squasher.ai/quickstart).

## Repositories

- [squasher-go](https://github.com/squasher-ai/squasher-go): the Go SDK.
- [signalbox](https://github.com/squasher-ai/signalbox): synthetic OpenTelemetry data for testing
  agents.

The JavaScript SDKs are on npm under [`@squasher-ai`](https://www.npmjs.com/org/squasher-ai).

## Links

[Website](https://squasher.ai) · [Docs](https://docs.squasher.ai) ·
[Changelog](https://squasher.ai/changelog) · [Status](https://status.squasher.ai) ·
[X](https://x.com/SquasherAI)

Support: support@squasher.ai. Security reports: [squasher.ai/contact](https://squasher.ai/contact).

