# github-action-examples

This repo shows integration examples for [GitHub Actions](https://github.com/features/actions) into the [Sipfront App](https://app.sipfront.com).

## Preparing your repo

### Generate API credentials

In order to use the Sipfront API, you need to generate new API credentials. You can do this in the [Sipfront App](https://app.sipfront.com/subscription/apikey).

### Add API credentials to your repo

Navigate to your repo's settings page, and on the left hand menu go to `Secrets and variables`. Under `Actions`, click on `New repository secret` and create a new entry with the name `SIPFRONT_PUBLIC_KEY` and the value given in your Sipfront App. Do the same for another entry `SIPFRONT_SECRET_KEY` with the secret key value given in your Sipfront App.








