<p align="center">
  <img src="assets/colitu.png" width="120" alt="Colitu">
</p>

<h1 align="center">Colitu</h1>

<p align="center">
  Open-source VPN built for restricted and unstable networks.
</p>

<p align="center">
  <a href="https://status.colitu.com"><img src="https://img.shields.io/endpoint?url=https://status.colitu.com/api/github-badge/network&style=for-the-badge" alt="VPN Network"></a>
  <a href="https://status.colitu.com"><img src="https://img.shields.io/endpoint?url=https://status.colitu.com/api/github-badge/api&style=for-the-badge" alt="API"></a>
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

<a href="https://status.colitu.com"><img src="https://status.colitu.com/api/github-badge/overall.svg" alt="Colitu Network status"></a>

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

## Live badges

Ready to paste into any README. Every badge reads the same checks as
[status.colitu.com](https://status.colitu.com) and changes on its own when something
goes down (green → yellow → red).

| Badge | Shows | Image |
|---|---|---|
| <img src="https://status.colitu.com/api/github-badge/overall.svg" alt="Colitu Network"> | Whole service: online locations, or *Major outage* | `status.colitu.com/api/github-badge/overall.svg` |
| <img src="https://status.colitu.com/api/github-badge/network.svg" alt="VPN Network"> | Online VPN locations | `status.colitu.com/api/github-badge/network.svg` |
| <img src="https://status.colitu.com/api/github-badge/api.svg" alt="API"> | Sign-in, accounts and the API the apps use | `status.colitu.com/api/github-badge/api.svg` |
| <img src="https://status.colitu.com/api/github-badge/website.svg" alt="Website"> | colitu.com and the account portal | `status.colitu.com/api/github-badge/website.svg` |
| <img src="https://status.colitu.com/api/github-badge/downloads.svg" alt="Downloads"> | Installers and auto-update files | `status.colitu.com/api/github-badge/downloads.svg` |
| <img src="https://status.colitu.com/api/github-badge/payments.svg" alt="Payments"> | Checkout and payment methods | `status.colitu.com/api/github-badge/payments.svg` |
| <img src="https://status.colitu.com/api/github-badge/docs.svg" alt="Docs"> | docs.colitu.com help centre | `status.colitu.com/api/github-badge/docs.svg` |

**Colitu style** — the whole set in one line:

```markdown
[![Colitu Network](https://status.colitu.com/api/github-badge/overall.svg)](https://status.colitu.com)
[![VPN Network](https://status.colitu.com/api/github-badge/network.svg)](https://status.colitu.com)
[![API](https://status.colitu.com/api/github-badge/api.svg)](https://status.colitu.com)
[![Website](https://status.colitu.com/api/github-badge/website.svg)](https://status.colitu.com)
[![Downloads](https://status.colitu.com/api/github-badge/downloads.svg)](https://status.colitu.com)
```

**shields.io style:**

```markdown
[![Network](https://img.shields.io/endpoint?url=https://status.colitu.com/api/github-badge/network)](https://status.colitu.com)
```

Add `&style=for-the-badge` (or `flat-square`, `plastic`) to the shields.io URL to change its look.

<details>
<summary>Endpoint reference</summary>

| URL | Returns |
|---|---|
| `/api/github-badge/<name>` | shields.io endpoint JSON (`schemaVersion`, `label`, `message`, `color`) |
| `/api/github-badge/<name>.svg` | the Colitu badge image |
| `/api/github-badge/<name>.json` | every component and location with its state, plus all badge links |

`<name>` is one of `overall`, `network`, `api`, `website`, `downloads`, `payments`, `docs`.
Add `?label=Text` to change the label (up to 32 characters). Responses are cached for two minutes.

During a full outage the overall badge reads:

```json
{ "schemaVersion": 1, "label": "Colitu Network", "message": "Major outage", "color": "red" }
```

</details>

---

## Open source

The Android, Windows and Linux apps are open source under the GPL-3.0 license. Release
builds can be checked against their source: every GitHub release carries
`SHA256SUMS`, and [colitu.com/open-source](https://colitu.com/open-source)
explains how to verify a download.

Security issues: [security@colitu.com](mailto:security@colitu.com)
