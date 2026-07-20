# ExpiryRx v1.1

## Added in this release
- Improved PWA update behavior to reduce stale-cache problems
- Manual refresh/update button
- New-version notification banner
- CSV inventory export
- Full JSON backup
- Gmail recipient settings
- Test email draft containing critical-expiry information
- Version label and updated service-worker cache

## Email limitation
The Test Email feature opens a prepared email draft using the device's configured mail application. Fully automatic Gmail delivery requires:
1. A secure backend
2. Google OAuth authorization
3. Environment variables on Vercel
4. A database or scheduled job for automatic checks

No Gmail password is stored in this application.

## Deploy
Upload all files in this folder directly to the root of the GitHub repository and commit them. Vercel should redeploy automatically.
