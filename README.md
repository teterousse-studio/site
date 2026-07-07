# Apartment Tête Rousse website

Source for the Apartment Tête Rousse website at https://chaletteterousse.com.

## Structure

- `public/` contains the complete static website deployed to Cloudflare Pages.
- `.github/workflows/` contains the deployment workflow.

## Safe publishing workflow

1. Make changes on a separate branch.
2. Check the Cloudflare preview deployment.
3. Merge the approved change into `main`.
4. Cloudflare deploys `public/` automatically.

Never commit passwords, API tokens, form-service secrets, or personal information.
