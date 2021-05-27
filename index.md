---
layout: front
title: QUIC Working Group
---

## Upcoming Meetings

[IETF 111, July 26-30, 2021](https://github.com/quicwg/wg-materials/blob/master/ietf111/agenda.md)

## Our Documents

Our current documents cover different aspects of the 'core' QUIC protocol, define a mapping of HTTP semantics to it, and cover selected other topics.

* **RFCs**
  * **RFC 8999 - Version-Independent Properties of QUIC** -
    [HTML](https://www.rfc-editor.org/rfc/rfc8999.html) /
    [TXT](https://www.rfc-editor.org/rfc/rfc8999.txt) /
    [PDF](https://www.rfc-editor.org/rfc/rfc8999.pdf)
  * **RFC 9000 - QUIC: A UDP-Based Multiplexed and Secure Transport** -
    [HTML](https://www.rfc-editor.org/rfc/rfc9000.html) /
    [TXT](https://www.rfc-editor.org/rfc/rfc9000.txt) /
    [PDF](https://www.rfc-editor.org/rfc/rfc9000.pdf)
  * **RFC 9001 - Using TLS to Secure QUIC** -
    [HTML](https://www.rfc-editor.org/rfc/rfc9001.html) /
    [TXT](https://www.rfc-editor.org/rfc/rfc9001.txt) /
    [PDF](https://www.rfc-editor.org/rfc/rfc9001.pdf)
  * **RFC 9002 - QUIC Loss Detection and Congestion Control** -
    [HTML](https://www.rfc-editor.org/rfc/rfc9002.html) /
    [TXT](https://www.rfc-editor.org/rfc/rfc9002.txt) /
    [PDF](https://www.rfc-editor.org/rfc/rfc9002.pdf)


* **In-progress documents**
  * **HTTP/3** -
    [Editors' Draft](https://quicwg.github.io/base-drafts/draft-ietf-quic-http.html) /
    [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-http) /
    [Repo](https://github.com/quicwg/base-drafts/) /
    [Open Issues](https://github.com/quicwg/base-drafts/issues?utf8=✓&q=is%3Aissue%20is%3Aopen%20label%3A-http%20label%3Adesign)
  * **QPACK** -
    [Editors' Draft](https://quicwg.github.io/base-drafts/draft-ietf-quic-qpack.html) /
    [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-qpack) /
    [Repo](https://github.com/quicwg/base-drafts/) /
    [Open Issues](https://github.com/quicwg/base-drafts/issues?utf8=✓&q=is%3Aissue%20is%3Aopen%20label%3A-qpack%20label%3Adesign)
  * **Load Balancers** -
    [Editors' Draft](https://quicwg.github.io/load-balancers/draft-ietf-quic-load-balancers.html) /
    [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-load-balancers) /
    [Repo](https://github.com/quicwg/load-balancers/) /
    [Open Issues](https://github.com/quicwg/load-balancers/issues?utf8=✓&q=is%3Aissue%20is%3Aopen)
  * **Operations** -
      * **Applicability**
        [Editors' Draft](https://quicwg.github.io/ops-drafts/draft-ietf-quic-applicability.html) /
        [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-applicability) /
        [Repo](https://github.com/quicwg/ops-drafts/) /
        [Open Issues](https://github.com/quicwg/ops-drafts/issues?utf8=✓&q=is%3Aissue%20is%3Aopen)
      * **Manageability**
        [Editors' Draft](https://quicwg.github.io/ops-drafts/draft-ietf-quic-manageability.html) /
        [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-manageability) /
        [Repo](https://github.com/quicwg/ops-drafts/) /
        [Open Issues](https://github.com/quicwg/ops-drafts/issues?utf8=✓&q=is%3Aissue%20is%3Aopen)
  * **Extensions**
      * **Datagram**
        [Editors' Draft](https://quicwg.github.io/datagram/draft-ietf-quic-datagram.html) /
        [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-datagram) /
        [Repo](https://github.com/quicwg/datagram/) /
        [Open Issues](https://github.com/quicwg/datagram/issues?utf8=✓&q=is%3Aissue%20is%3Aopen)
      * **Version Negotiation**
        [Editors' Draft](https://quicwg.github.io/version-negotiation/draft-ietf-quic-version-negotiation.html) /
        [WG Draft](https://datatracker.ietf.org/doc/html/draft-ietf-quic-version-negotiation) /
        [Repo](https://github.com/quicwg/version-negotiation/) /
        [Open Issues](https://github.com/quicwg/version-negotiation/issues?utf8=✓&q=is%3Aissue%20is%3Aopen)


## Implementing QUIC

We have a number of [experimental implementations](https://github.com/quicwg/base-drafts/wiki/Implementations) in progress. The current goal for interop testing is the [21st Implementation Target](https://github.com/quicwg/base-drafts/wiki/21st-Implementation-Draft).

Implementers should join the [quicdev Slack](https://quicdev.slack.com/) to coordinate testing; contact the [WG chairs](mailto:quic-chairs@ietf.org) for an invitation. Note that discussions on Slack are considered IETF contributions under "Note Well".

[Automated, continuous interop testing](https://interop.seemann.io/) is performed for participating QUIC implementations. Implementers are encouraged to join this effort by making [compatible Docker images](https://github.com/marten-seemann/quic-interop-runner#building-a-quic-endpoint) of their implementations available.

## See Also

* [Late Stage Processing Queue](https://github.com/quicwg/base-drafts/projects/5) (base-drafts)
* [Issues that have consensus](https://github.com/quicwg/base-drafts/issues?utf8=✓&q=is%3Aissue%20label%3Ahas-consensus%20) (base-drafts)
* [Issues that need consensus confirmed](https://github.com/quicwg/base-drafts/issues?utf8=✓&q=is%3Aissue%20is%3Aclosed%20-label%3Ainvalid%20-label%3Aeditorial%20-label%3Ahas-consensus%20) (base-drafts)
* [Working Group materials](https://github.com/quicwg/wg-materials) -- agendas, minutes, etc.
* [Related Activities](https://github.com/quicwg/base-drafts/wiki/Related-Activities) -- QUIC extensions and applications that *might* happen

----
