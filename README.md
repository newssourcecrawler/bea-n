# bea-n

bea-n is a local path, message, and device failure evidence case former.

It reads pasted or selected failure evidence and forms a bounded local case report. It is built for noisy developer environments where logs mention Kafka, MQTT, DNS, TLS, HTTP, Bluetooth, IoT devices, or generic path failures.

bea-n does not connect to brokers, networks, DNS, Bluetooth devices, infrastructure, or services. It does not collect credentials, rewrite code, rewrite configuration, or apply fixes.

## Install

macOS arm64 binary releases are published from this repository.

Homebrew install instructions will be added after the tap is prepared.

## Editor wrappers

The bea-n CLI is used by editor wrappers such as:

- bea-n JetBrains Plugin

## Release

Current release target:

```text
v2026.1.0
bea-n-2026.1.0-macos-arm64.tar.gz
```
