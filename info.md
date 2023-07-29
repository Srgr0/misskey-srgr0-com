# misskey.srgr0.com
## About
Personal Misskey instance of [Srgr0](https://github.com/srgr0).

## Spec
### Server
- Located in Japan
- Virtualized
- Xeon CPU
- 2GB RAM
- SSD 50GB + 50GB

### OS
Ubuntu 20.04.6 LTS

### Network
50Mbps (Software-based bandwidth limit)  
Traffic is forwarded to the Cloudflare network by the Cloudflare Tunnel and exposed to the Internet.

### Object Storage
Cloudflare R2 ([Usage](https://github.com/Srgr0/misskey_cloudflare-r2-usage/blob/main/output.csv))

### Software
Misskey 13.13.2 (systemd/local-nginx)

## Relay
The instance is connected to the following relay services:
- [YUKIMOCHI Toot Relay Service](https://relay.toot.yukimochi.jp/)
- [Fedibird Relay Service](https://relay.fedibird.com/)
- [ハッシュタグリレー](https://hashtag-relay.dtp-mstdn.jp/)
- [taruntarun relay](https://relay.taruntarun.net/)

