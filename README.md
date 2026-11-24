# Noel Bennett

Software for your own network: self-hosted servers, a client, and the build
pipeline that produces the firmware they run on. Everything below is open
source and runs on hardware you control.

Sites in English and Traditional Chinese:
<https://noelbennettz.github.io/> · [中文](https://noelbennettz.github.io/zh.html)

## Projects

| | Project | What it does | Stack |
| --- | --- | --- | --- |
| 01 | [Hy2droid](https://github.com/noelbennettz/Hy2droid) | Hysteria 2 client for Android. Paste a `hysteria2://` link or scan a QR code and the phone's traffic goes out through your server: full-tunnel IPv4/IPv6, Android 11 or newer, no root, no Google Play Services. | Kotlin · Compose · AGPL-3.0 |
| 02 | [AmneziaWG Web UI](https://github.com/noelbennettz/amneziawg-ui) | A web panel for your own AmneziaWG server in one ~35 MB Docker image: servers and clients, `.conf`, QR and `vpn://` export, live traffic. | Go · Docker · AGPL-3.0 |
| 03 | [iMail](https://github.com/noelbennettz/imail) | A mail server for domains you own: SMTP, IMAPS and POP3S, a browser inbox, an admin console and per-domain certificates, on SQLite or MySQL/PostgreSQL. | Go · Vue · Docker · AGPL-3.0 |
| 04 | [OpenWrt x86 images](https://github.com/noelbennettz/actions-openwrt-x86) | OpenWrt 25.12 x86/64 firmware built from the official sources on GitHub Actions: Passwall with sing-box and Hysteria 2, 92 network drivers, seven languages. | Shell · Actions · MIT |
| 05 | [hs](https://github.com/noelbennettz/headscale-wrapper) | A name-based wrapper for the `headscale` CLI: `hs show laptop`, `hs expire phone`, `hs route add gw 10.0.0.0/8`. Bash and `jq`; no daemon, no state of its own. | Bash · MIT |

## Notes

Each repository's `README.md` and `DOCS.md` describe the current `main`; a
release keeps the documentation it shipped with at its own tag
(`git show <tag>:DOCS.md`). The project sites are plain HTML/CSS in
[`noelbennettz.github.io`](https://github.com/noelbennettz/noelbennettz.github.io).
