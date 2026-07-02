# Swift WHATWG

Swift implementations of WHATWG (Web Hypertext Application Technology Working Group) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-whatwg-<spec>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`WHATWG_HTML`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift WHATWG is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by WHATWG.

## Coverage

| Package | Specification |
|---|---|
| [swift-whatwg-html](https://github.com/swift-whatwg/swift-whatwg-html) | HTML Living Standard |
| [swift-whatwg-url](https://github.com/swift-whatwg/swift-whatwg-url) | URL Standard |

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-whatwg/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
