# Changelog

All notable changes to ja3-ja4-tls-fingerprinting will be documented in this file.

## [0.1.0] - 2026-01-05
- Initial commit: TLS handshake fingerprinting engine in Rust

## [0.1.1] - 2026-01-06
- feat: implement JA3/JA3S hashing from raw Client/Server Hello packets

## [0.1.2] - 2026-01-08
- feat: add JA4 suite support (JA4, JA4H, JA4T, JA4X) with zero-copy parser

## [0.1.3] - 2026-01-11
- perf: optimize hash computation pipeline for multi-gigabit PCAP streams

