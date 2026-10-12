<div align="center">

# OSA Alias

**DNS-based domain redirection.**

Open source alternative to **Google Domains forwarding**. Part of the [Open Software Alliance](https://github.com/OpenSoftwareAlliance) suite.

</div>

---

## Features

- Domain redirects configured only through DNS records
- Path and wildcard redirect rules
- Automatic HTTPS via Let's Encrypt
- No accounts, no dashboard

## Tech stack

- **Current:** Go
- **Target:** Next.js + TypeScript on Cloudflare Workers (see [migration research](https://github.com/OpenSoftwareAlliance/alias/issues/2))

## Roadmap

- [Open source landscape research](https://github.com/OpenSoftwareAlliance/alias/issues/1)
- [Migration research: React/Next.js + TypeScript on Cloudflare Workers](https://github.com/OpenSoftwareAlliance/alias/issues/2)
- [All issues](https://github.com/OpenSoftwareAlliance/alias/issues)

## Self-hosting

Installation and configuration follow the upstream project for now: see the [redirect.name documentation](https://github.com/frolic/redirect.name#readme).

## The OSA suite

| Product | What it does | Alternative to |
|---|---|---|
| [OSA Pad](https://github.com/OpenSoftwareAlliance/pad) | Real-time collaborative document editor. | Google Docs |
| [OSA Sheet](https://github.com/OpenSoftwareAlliance/sheet) | Online collaborative spreadsheet. | Google Sheets |
| [OSA Cal](https://github.com/OpenSoftwareAlliance/cal) | Scheduling and booking pages. | Google Calendar (appointment schedules) |
| [OSA Mail](https://github.com/OpenSoftwareAlliance/mail) | Email forwarding and hosting for custom domains. | Gmail |
| [OSA Meet](https://github.com/OpenSoftwareAlliance/meet) | Secure peer-to-peer video meetings. | Google Meet |
| [OSA Draw](https://github.com/OpenSoftwareAlliance/draw) | Infinite canvas whiteboard. | Google Drawings / Jamboard |
| [OSA Drop](https://github.com/OpenSoftwareAlliance/drop) | Local file sharing in the browser. | Quick Share |
| [OSA Share](https://github.com/OpenSoftwareAlliance/share) | Simple temporary file hosting. | Google Drive (file links) |
| [OSA Share Admin](https://github.com/OpenSoftwareAlliance/share-admin) | Moderation panel for OSA Share. | Google Drive admin |
| [OSA Bin](https://github.com/OpenSoftwareAlliance/bin) | Zero-knowledge encrypted pastebin. | Google Keep (secure notes) |
| [OSA Snip](https://github.com/OpenSoftwareAlliance/snip) | Self-hosted code snippets and gists. | Google Keep (snippets) |
| [OSA Short](https://github.com/OpenSoftwareAlliance/short) | URL shortener with analytics. | goo.gl |
| [OSA Alias](https://github.com/OpenSoftwareAlliance/alias) | DNS-based domain redirection. | Google Domains forwarding |
| [OSA Page](https://github.com/OpenSoftwareAlliance/page) | Link-in-bio pages. | Google Sites |
| [OSA Feedback](https://github.com/OpenSoftwareAlliance/feedback) | Feedback boards and public roadmaps. | Google Forms (product feedback) |
| [OSA Jam](https://github.com/OpenSoftwareAlliance/jam) | Live audio rooms. | Google Meet (audio) |
| [OSA Micro](https://github.com/OpenSoftwareAlliance/micro) | Ready-to-use micro service APIs. | Google Cloud APIs |
| [OSA Username](https://github.com/OpenSoftwareAlliance/username) | Check username availability on 100+ sites. | - |
| [OSA Status](https://github.com/OpenSoftwareAlliance/status) | Uptime monitor and status page for the OSA services. | - |

## License and credits

OSA Alias is based on [redirect.name](https://github.com/frolic/redirect.name). Credit for the original work goes to its authors.

License: MIT. See the [LICENSE](LICENSE) file in this repository.
