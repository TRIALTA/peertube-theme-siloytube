# SiloyTube
## PeerTube theme
A simple theme derived from the official PeerTube "dark" theme with adjustments for SiloyTube.

### Development installation
- You must have a peertube docker instance running and connected via peertube-cli
- Run `npm run dev` to bump the version and upload a recent version of the theme

### Production installation
- Put the repo onto your peertube instance
- Run `peertube-cli plugins install --path "/peertube-theme-siloytube"` where `/peertube-theme-siloytube` is the path to this repo