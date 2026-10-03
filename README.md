<p align="center">
  <img src="assets/colitu.png" width="120" alt="Colitu">
</p>

<h1 align="center">Colitu</h1>

<p align="center">
  Open-source VPN built for restricted and unstable networks.
</p>

<p align="center">
  <a href="https://status.colitu.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fstatus.colitu.com%2Fapi%2Fgithub-badge%3Fcomponent%3Dnetwork&style=for-the-badge" alt="VPN Network"></a>
  <a href="https://status.colitu.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fstatus.colitu.com%2Fapi%2Fgithub-badge%3Fcomponent%3Dapi&style=for-the-badge" alt="API"></a>
  <a href="https://colitu.com/open-source"><img src="https://img.shields.io/badge/Open%20Source-Android%20%C2%B7%20Windows%20%C2%B7%20Linux-7c6cff?style=for-the-badge&labelColor=101014" alt="Open Source"></a>
  <a href="https://github.com/colitu/colitu-android/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-7c6cff?style=for-the-badge&labelColor=101014" alt="GPL-3.0"></a>
</p>

<p align="center">
  Hysteria2 • VLESS Reality • VLESS XHTTP • Trojan • Shadowsocks 2022
</p>

<p align="center">
  <a href="https://colitu.com">Website</a> •
  <a href="https://docs.colitu.com">Docs</a> •
  <a href="https://status.colitu.com">Status</a> •
  <a href="https://colitu.com/download">Download</a> •
  <a href="https://colitu.com/security">Security</a>
</p>

---

## Network status

<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge?format=svg" alt="Colitu Network status"></a>

<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge?component=network&format=svg" alt="VPN Network"></a>
<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge?component=api&format=svg" alt="API"></a>
<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge?component=website&format=svg" alt="Website"></a>
<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge?component=downloads&format=svg" alt="Downloads"></a>

These badges are live: they are drawn from the same checks as
[status.colitu.com](https://status.colitu.com) and change on their own when a
location or service goes down.

[View live network status →](https://status.colitu.com)

---

## Connection technologies

The apps choose between these methods on their own and keep the first one that
actually carries traffic on your network.

| Method | In the apps | Transport |
|---|---|---|
| Hysteria2 | Fast | QUIC (UDP) |
| VLESS Reality | Stealth | TCP + Reality TLS |
| VLESS XHTTP | Resilient | HTTP + Reality TLS |
| Trojan | Classic | TCP + TLS |
| Shadowsocks 2022 | Light | TCP / UDP |

---

## Apps

| Platform | Repository | Build | Release |
|---|---|---|---|
| Android & Android TV | [colitu-android](https://github.com/colitu/colitu-android) | [![Android CI](https://img.shields.io/github/actions/workflow/status/colitu/colitu-android/ci.yml?branch=main&style=flat-square&label=build&labelColor=101014)](https://github.com/colitu/colitu-android/actions/workflows/ci.yml) | [![Release](https://img.shields.io/github/v/release/colitu/colitu-android?style=flat-square&labelColor=101014&color=7c6cff)](https://github.com/colitu/colitu-android/releases/latest) |
| Windows | [colitu-windows](https://github.com/colitu/colitu-windows) | [![Windows build](https://img.shields.io/github/actions/workflow/status/colitu/colitu-windows/build.yml?branch=main&style=flat-square&label=build&labelColor=101014)](https://github.com/colitu/colitu-windows/actions/workflows/build.yml) | [![Release](https://img.shields.io/github/v/release/colitu/colitu-windows?style=flat-square&labelColor=101014&color=7c6cff)](https://github.com/colitu/colitu-windows/releases/latest) |
| Linux | [colitu-linux](https://github.com/colitu/colitu-linux) | [![Linux tests](https://img.shields.io/github/actions/workflow/status/colitu/colitu-linux/test.yml?branch=main&style=flat-square&label=build&labelColor=101014)](https://github.com/colitu/colitu-linux/actions/workflows/test.yml) | [![Release](https://img.shields.io/github/v/release/colitu/colitu-linux?include_prereleases&style=flat-square&labelColor=101014&color=7c6cff)](https://github.com/colitu/colitu-linux/releases) |
| iOS | — | — | [TestFlight beta](https://colitu.com/download/ios) |

Downloads for every platform: [colitu.com/download](https://colitu.com/download)

---

## Badges for your README

The status endpoint is public. Use it through shields.io:

```markdown
[![Colitu Network](https://img.shields.io/endpoint?url=https%3A%2F%2Fstatus.colitu.com%2Fapi%2Fgithub-badge&style=for-the-badge)](https://status.colitu.com)
```

or as Colitu's own badge image:

```markdown
[![Colitu Network](https://status.colitu.com/api/github-badge?format=svg)](https://status.colitu.com)
```

| Parameter | Values |
|---|---|
| `component` | `overall` (default), `network`, `api`, `website`, `downloads`, `payments`, `docs` |
| `format` | `shields` (default, shields.io endpoint JSON), `svg` (badge image), `full` (all components and locations as JSON) |
| `label` | optional label text, up to 32 characters |

---

## Open source

The Android, Windows and Linux apps are open source under the GPL-3.0 license. Release
builds can be checked against their source: every GitHub release carries
`SHA256SUMS`, and [colitu.com/open-source](https://colitu.com/open-source)
explains how to verify a download.

Security issues: [security@colitu.com](mailto:security@colitu.com)
