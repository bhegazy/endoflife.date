---
title: Istio
layout: post
category: service
sortReleasesBy: "releaseCycle"
changelogTemplate: "https://istio.io/latest/docs/releases/supported-releases/#support-status-of-istio-releases"

releases:
  - releaseCycle: "1.13"
    eol: 2022-10
    release: 2022-02-11
  - releaseCycle: "1.12"
    eol: 2022-06
    release: 2021-11-18
  - releaseCycle: "1.11"
    eol: 2022-03
    release: 2021-08-12
  - releaseCycle: "1.10"
    eol: 2022-01-07
    release: 2021-05-18
  - releaseCycle: "1.9"
    eol: 2021-10-08
    release: 2021-02-09
  - releaseCycle: "1.8"
    eol: 2021-05-12
    release: 2020-11-10
  - releaseCycle: "1.7"
    eol: 2021-02-25
    release: 2020-08-21
  - releaseCycle: "1.6 and earlier"

iconSlug: istio

permalink: /istio
releasePolicyLink: https://istio.io/latest/docs/releases/supported-releases/#support-status-of-istio-releases"
activeSupportColumn: false
releaseColumn: true
releaseDateColumn: true
eolColumn: End of Support
command: istioctl version
---
> [Istio](https://istio.io) is an open source service mesh that layers transparently onto existing distributed applications. Istio’s powerful features provide a uniform and more efficient way to secure, connect, and monitor services. Istio is the path to load balancing, service-to-service authentication, and monitoring – with few or no service code changes

Istio produce new builds of Istio for each commit. Around once a quarter, Istio build a minor release and run through several additional tests as well as release qualification. Istio release patch versions for issues found in minor releases.

You can find available releases on the [releases page](https://github.com/istio/istio/releases), and if you’re the adventurous type, you can learn about our development builds on the [development builds wiki](https://github.com/istio/istio/wiki/Dev%20Builds). You can find high-level releases notes for each minor and patch release [here](https://istio.io/latest/news).

## Upgrading

Istio recommends [canary upgrades][canary-upgrade], however, there are also [in-place upgrade][in-place-upgrade].

[canary-upgrade]: https://istio.io/latest/docs/setup/upgrade/canary/
[in-place-upgrade]: https://istio.io/latest/docs/setup/upgrade/in-place/
