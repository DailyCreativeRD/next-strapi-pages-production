# Next.js + Strapi Production Promotion Prototype

This repository contains no Next.js source and never contacts Strapi. It promotes a production-ready static artifact created by an approved staging workflow run.

## GitHub repository settings

Configure this repository variable:

- `STAGING_REPOSITORY`, for example `your-account/next-strapi-pages-prototype`

Configure this repository secret:

- `STAGING_ARTIFACT_TOKEN`: a fine-grained token with Actions read access to the staging repository

Under **Settings -> Pages**, choose **GitHub Actions** as the publishing source.

After reviewing staging, manually run **Promote approved staging build** and enter the successful staging workflow run ID.

