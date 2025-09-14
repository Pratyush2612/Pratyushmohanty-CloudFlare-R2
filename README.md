# Pratyushmohanty-CloudFlare-R2
This project automates DB backups every 12 hours, uploading to Cloudflare R2's free tier. It requires a server (e.g., Digital Ocean) with a MongoDB instance and seeded data. Backups can be scheduled via cron jobs or GitHub Actions using mongodump and AWS CLI. A stretch goal includes a script to download and restore the latest backup from R2.
https://github.com/yourusername/automated-db-backups
