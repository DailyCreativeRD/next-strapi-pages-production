# Next.js + Strapi Production Promotion Prototype

This repository contains no Next.js source and never contacts Strapi. It promotes a production-ready static artifact created by an approved staging workflow run.

## GitHub repository settings

Configure this repository variable:

- `STAGING_REPOSITORY`, for example `your-account/next-strapi-pages-prototype`

Under **Settings -> Pages**, choose **GitHub Actions** as the publishing source.

After reviewing staging, manually run **Promote approved staging build** and enter the successful staging workflow run ID. The workflow downloads the matching public release asset and verifies its SHA-256 checksum before deployment.

This token-free prototype assumes the staging repository is public. For a private production staging repository, use a short-lived GitHub App installation token and a protected staging host.
