# 🌐 Cloudflare DDNS Updater

This Bash script automates the process of updating a DNS A record on Cloudflare with the current public IP address of the machine it's running on. It utilizes the Cloudflare API to perform the update.

## Prerequisites

Before using this script, make sure you have the following:

- An active Cloudflare account
- API Token or Global API Key with appropriate permissions
- The domain hosted on Cloudflare
- The zone identifier of the domain
- The DNS record

## How to Use

1. **Configuration**: Open the script in a text editor and fill in the required details such as `auth_email`, `auth_key`, `zone_identifier`, `record_name`, etc.

2. **Run the Script**: Execute the script in your terminal by running `./cloudflare_ddns.sh`.

## Additional Notes

- Ensure the script has executable permissions (`chmod +x cloudflare_ddns.sh`).
- The script will log updates and errors using the system logger.
- Optional notifications can be configured for Slack and Discord.

🔔 Happy updating your DNS records with Cloudflare!.
