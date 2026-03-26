## GitHub Copilot Chat

- Extension: 0.41.1 (prod)
- VS Code: 1.113.0 (cfbea10c5ffb233ea9177d34726e6056e89913dc)
- OS: win32 10.0.26200 x64
- GitHub Account: guigui779

## Network

User Settings:
```json
  "http.systemCertificatesNode": true,
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 20.205.243.168 (1 ms)
- DNS ipv6 Lookup: Error (46 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (0 ms)
- Electron fetch (configured): HTTP 200 (59 ms)
- Node.js https: HTTP 200 (313 ms)
- Node.js fetch: HTTP 200 (54 ms)

Connecting to https://api.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.114.21 (1 ms)
- DNS ipv6 Lookup: Error (45 ms): getaddrinfo ENOTFOUND api.githubcopilot.com
- Proxy URL: None (0 ms)
- Electron fetch (configured): HTTP 200 (306 ms)
- Node.js https: HTTP 200 (1006 ms)
- Node.js fetch: HTTP 200 (309 ms)

Connecting to https://copilot-proxy.githubusercontent.com/_ping:
- DNS ipv4 Lookup: 52.175.140.176 (0 ms)
- DNS ipv6 Lookup: Error (47 ms): getaddrinfo ENOTFOUND copilot-proxy.githubusercontent.com
- Proxy URL: None (0 ms)
- Electron fetch (configured): HTTP 200 (127 ms)
- Node.js https: HTTP 200 (534 ms)
- Node.js fetch: HTTP 200 (125 ms)

Connecting to https://mobile.events.data.microsoft.com: HTTP 404 (273 ms)
Connecting to https://dc.services.visualstudio.com: HTTP 404 (241 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (1009 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (1033 ms)
Connecting to https://default.exp-tas.com: HTTP 400 (356 ms)

Number of system certificates: 68

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).