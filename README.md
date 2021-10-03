Private website using static site generator [Hugo](https://gohugo.io/)

## Deployment

### Prerequisites
Ensure hugo `v0.88.1` is installed.

The default deploy target is my website. If there is a need to deploy to some other target, add it under `config.toml`.
Example steps for using with [MINIO](https://min.io/) instance:
1. Create a new bucket called `website` and set it's `Access Policy` to `Public` (via web console or with `mc policy set download your_alias/website`).
2. Create a new user via MINIO web console and grant them e.g. `readwrite` policy (or some other policy assigned to your `website` bucket).

### Build and deploy
1. Build by running `hugo`
2. Deploy by running `AWS_ACCESS_KEY_ID="USERNAME" AWS_SECRET_ACCESS_KEY="PASSWORD" hugo deploy`
    - If deploying to MINIO instance, replace `USERNAME` with the name of the user having access to the `website` bucket and `PASSWORD` with their password.
