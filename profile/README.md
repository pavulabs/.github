<p align="center">
  <a href="https://pavulabs.github.io">
    <img src="https://pavulabs.github.io/assets/pavu-icon.png" width="112" alt="Pavu Labs logo">
  </a>
</p>

<h1 align="center">Pavu Labs</h1>

<p align="center"><strong>Privacy-first endpoint security for personal devices.</strong></p>

Pavu Labs is building local-first security software that helps people understand what applications do across network, process, and file activity. We focus on useful evidence, explainable findings, and a clear privacy boundary.

我们正在构建面向个人设备的本机优先安全软件，帮助用户理解应用的网络、进程与文件行为，同时坚持清晰、可验证的隐私边界。

## Our principles

- **Local first:** analysis and storage stay on the device by default.
- **Metadata, not content:** we do not decrypt TLS or collect passwords, cookies, network payloads, or complete file contents.
- **Explainable security:** findings include reasons, supporting evidence, and recommended actions.
- **Platform honesty:** unavailable permissions and collection limits are reported explicitly.
- **Shared architecture:** platform collectors feed a portable Rust core with consistent schemas and detection semantics.

## Current work

Pavu for macOS is in private beta. It uses Apple-supported system extension APIs to observe network-flow metadata. File-activity collection requires Apple's separately approved Endpoint Security entitlement and explicit user authorization.

[Visit the Pavu website](https://pavulabs.github.io) · [Read our security policy](../SECURITY.md)
