---
layout: subpage
title: QUIC Working Group - Packet sizes & PMTUD
---

This page collects the results of an informal survey of implementations'
approaches to MTU matters. It captures what default size an implementation picks
to start, whether they support (DPL)PMTUD, and whether they advertise a
max_udp_payload_size to their peer. Many implementations support configurability
of these options, so the values may not represent any specific deployment.

| Implementation | Default start packet size | (DPL)PMTUD supported | Default max_udp_payload_size |
| - | - | - | -|
| google quiche | 1250 | No | - |
| MsQuic | 1240 | Yes | Based on MTU of the socket/interface |
| mvfst | 1232 | No (experimented with and subsequently removed) | - |
| neqo | 1200 | Yes | - |
| ngtcp2 | 1200 | Yes | - |
| pico-quic | 1252 (IPv4), 1232 (IPv6) | Yes | 1440 |
| quinn | 1200 | Yes | - |
| quiche | 1200 | Yes | - |
| s2n-quic | 1200 | Yes | - |