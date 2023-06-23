# Self-Host Release Repository
Bitwarden's dedicated self-hosted release repository. This holds the installation scripts for our self-host project.

For any issues regarding a specific client application, please visit [bitwarden/clients](https://github.com/bitwarden/clients)

---
[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://marketplace.digitalocean.com/apps/bitwarden?action=deploy)

# Get started

```bash
curl -o bitwarden.sh "https://raw.githubusercontent.com/vinothvkr/bitwarden-self-host/master/bitwarden.sh" && chmod 700 bitwarden.sh
```

mkdir bwdata
mkdir letsencrypt
nano cloudflare.ini
dns_cloudflare_api_token=
chmod 600 cloudflare.ini