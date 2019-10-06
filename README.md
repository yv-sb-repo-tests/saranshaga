## Current build and deploy status

[![Netlify Status](https://api.netlify.com/api/v1/badges/f23c1733-0be5-4c61-b882-765f36ab41f3/deploy-status)](https://app.netlify.com/sites/saranshag/deploys)


# Stackbit Fresh Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.74.

Stackbit Fresh Theme original README is located [here](./README.theme.md).

The content of this site is managed by NetlifyCMS. Visit https://{yoursite-domain}/admin to manage site content.

# Running Your Site Locally

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5d99b8da158802001214dd14

1. Build the site and start the Hugo server with drafts enabled

        hugo server -D

1. Browse to [http://localhost:1313/](http://localhost:1313/)
