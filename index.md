---
layout: front
title: QUIC Working Group
---

## Published RFCs
### Core Specifications

The 'core' specifications comprising QUIC are:

* [RFC 8999](https://www.rfc-editor.org/rfc/rfc8999.html) - Version-Independent Properties of QUIC
* [RFC 9000](https://www.rfc-editor.org/rfc/rfc9000.html) - QUIC: A UDP-Based Multiplexed and Secure Transport
* [RFC 9001](https://www.rfc-editor.org/rfc/rfc9001.html) - Using TLS to Secure QUIC
* [RFC 9002](https://www.rfc-editor.org/rfc/rfc9002.html) - QUIC Loss Detection and Congestion Control

### QUIC Extensions

QUIC can be extended in several ways. The following have been
formally standardized as RFCs:

* [RFC 9221](https://www.rfc-editor.org/rfc/rfc9221.html) - An Unreliable Datagram Extension to QUIC
* [RFC 9287](https://www.rfc-editor.org/rfc/rfc9287.html) - Greasing the QUIC Bit
* [RFC 9368](https://www.rfc-editor.org/rfc/rfc9368.html) - Compatible Version Negotiation for QUIC
* [RFC 9369](https://www.rfc-editor.org/rfc/rfc9369.html) - QUIC Version 2

### Applicability, Manageability, and Operations

Specifications providing considerations for application protocol developers
using QUIC, and deployment / network operators managing/carrying QUIC:

* [RFC 9308](https://www.rfc-editor.org/rfc/rfc9308.html) - Applicability of the QUIC Transport Protocol
* [RFC 9312](https://www.rfc-editor.org/rfc/rfc9312.html) - Manageability of the QUIC Transport Protocol

### HTTP/3 and QPACK

We originated the HTTP/3 and QPACK RFCs. Ownership of these drafts has now
transferred back to the [HTTP WG](https://httpwg.org).

* [RFC 9114](https://www.rfc-editor.org/rfc/rfc9114.html) - HTTP/3
* [RFC 9204](https://www.rfc-editor.org/rfc/rfc9204.html) - QPACK

## In-progress documents

In-progress documents for continued maintenance and evolution of QUIC, as described
further in [our charter](https://datatracker.ietf.org/wg/quic/about/).

* [Load Balancers](https://quicwg.github.io/load-balancers/draft-ietf-quic-load-balancers.html) -
  [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-load-balancers) <img src="asset/ietf-logo-white.svg" width=20>  /
  [GitHub Repo](https://github.com/quicwg/load-balancers) <img src="asset/github-mark.svg" width=20>
* [Acknowledgement Frequency](https://quicwg.org/ack-frequency/draft-ietf-quic-ack-frequency.html) -
  [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-ack-frequency) <img src="asset/ietf-logo-white.svg" width=20> /
  [GitHub Repo](https://github.com/quicwg/ack-frequency) <img src="asset/github-mark.svg" width=20>
* qlog
    * [Main logging Schema](https://quicwg.org/qlog/draft-ietf-quic-qlog-main-schema.html) -
      [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-qlog-main-schema) <img src="asset/ietf-logo-white.svg" width=20> /
      [GitHub Repo](https://github.com/quicwg/qlog) <img src="asset/github-mark.svg" width=20>
    * [QUIC event definitions](https://quicwg.org/qlog/draft-ietf-quic-qlog-quic-events.html) -
      [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-qlog-quic-events.html) <img src="asset/ietf-logo-white.svg" width=20> /
      [GitHub Repo](https://github.com/quicwg/qlog) <img src="asset/github-mark.svg" width=20>
    * [HTTP/3 event definitions](https://quicwg.org/qlog/draft-ietf-quic-qlog-h3-events.html) -
      [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-qlog-h3-events.html) <img src="asset/ietf-logo-white.svg" width=20> /
      [GitHub Repo](https://github.com/quicwg/qlog) <img src="asset/github-mark.svg" width=20>
* [Multipath](https://quicwg.org/multipath/draft-ietf-quic-multipath.html) -
  [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-multipath) <img src="asset/ietf-logo-white.svg" width=20> /
  [GitHub Repo](https://github.com/quicwg/multipath) <img src="asset/github-mark.svg" width=20>
* [Reliable Reset](https://quicwg.org/reliable-stream-reset/draft-ietf-quic-reliable-stream-reset.html) -
  [Datatracker](https://datatracker.ietf.org/doc/html/draft-ietf-quic-reliable-stream-reset) <img src="asset/ietf-logo-white.svg" width=20> /
  [GitHub Repo](https://github.com/quicwg/reliable-stream-reset) <img src="asset/github-mark.svg" width=20>


## Implementing QUIC

There are a range of [implementations and tools](https://quicwg.org/staging.quicwg.github.io/implementations.html),
with a range of support for features of the core protocol and extensions.

Implementers should join the [quicdev Slack](https://quicdev.slack.com/) to
coordinate testing; contact the [WG chairs](mailto:quic-chairs@ietf.org) for an
invitation. Note that discussions on Slack are considered IETF contributions
under "Note Well".

[Automated, continuous interop testing](https://interop.seemann.io/) is
performed for participating QUIC implementations. Implementers are encouraged to
join this effort by making [compatible Docker images](https://github.com/marten-seemann/quic-interop-runner#building-a-quic-endpoint) of their implementations available.

## Upcoming Meetings

* IETF 122 Bangkok, 19 March 2025, Session II 13:00-15:00 local time

## Reporting Vulnerabilities

If you believe you've discovered a vulnerability in the QUIC protocol (or related
IETF protocols) please see the IETF's guidance on [how to report
these](https://www.ietf.org/standards/rfcs/vulnerabilities/).

If you believe you've discovered an implementation vulnerability in a product,
open source project, or service using QUIC, then you should report these
directly to the responsible party. The IETF does not have a formal means to
reach these parties and cannot do so on your behalf. Implementers or operators
often provide their own publicly-available disclosure documents that provide
contact details and guidelines for reporters. The [implementations and
tools](https://quicwg.org/staging.quicwg.github.io/implementations.html) page
may include a link to such documents under the "Vulnerability reporting" field.
If you believe the same vulnerability affects multiple different implementations
or deployments, then a coordinated responsible disclosure may be the best path
forward; please reach out to [WG chairs](mailto:quic-chairs@ietf.org) for
further information.

## See Also

* [Working Group materials](https://github.com/quicwg/wg-materials) -- agendas, minutes, etc.

----
