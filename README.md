# Self-Host Release Repository
Bitwarden's dedicated self-hosted release repository. This holds the installation scripts for our self-host project.

For any issues regarding a specific client application, please visit [bitwarden/clients](https://github.com/bitwarden/clients)

---
[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://marketplace.digitalocean.com/apps/bitwarden?action=deploy)

# Get started

Follow the steps mentioned [here](https://bitwarden.com/help/install-on-premise-linux/#create-bitwarden-local-user-directory) before running the below command.

```bash
curl -o bitwarden.sh "https://raw.githubusercontent.com/vinothvkr/bitwarden-self-host/master/bitwarden.sh" && chmod 700 bitwarden.sh
```

```bash
mkdir bwdata && mkdir bwdata/letsencrypt
```

```bash
nano bwdata/letsencrypt/cloudflare.ini
```

```bash
dns_cloudflare_api_token=XXXXXXXXXXXXXXXXXXX
```

```bash
chmod 600 bwdata/letsencrypt/cloudflare.ini
```

```bash
./bitwarden.sh install
```