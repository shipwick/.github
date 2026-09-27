**Production deployments on your own server.**

Shipwick runs your Docker applications on one Linux server: rolling deployments
with health checks and rollback, HTTPS, scheduled jobs, backups, encrypted
secrets, tokens with roles and a dashboard, from one small config file.

| | |
|---|---|
| [shipwick](https://github.com/shipwick/shipwick) | The agent, the `shipwick` CLI and the dashboard |
| [website](https://github.com/shipwick/website) | [shipwick.com](https://shipwick.com): the documentation |
| [homebrew-tap](https://github.com/shipwick/homebrew-tap) | `brew install shipwick/tap/shipwick` |
| [deploy](https://github.com/shipwick/deploy) | `uses: shipwick/deploy@v1`: deploy from GitHub Actions |

Start here: [How it fits together](https://shipwick.com/docs/getting-started/how-it-fits),
then [Install Shipwick on a server](https://shipwick.com/docs/getting-started/install).
Found a vulnerability? [Report it privately](https://github.com/shipwick/shipwick/security/policy).
