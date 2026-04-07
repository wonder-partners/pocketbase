# Pocketbase on Railway

Open Source backend for your next SaaS and Mobile app in 1 file.

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/g6m4Cm?referralCode=HvqZ7W)

## Build arguments

> `PB_VERSION` is a build-time argument, not a runtime environment variable. Change it only if you want to build the image with another PocketBase version.

| Argument     | Required | Default  | Description                                           |
| ------------ | -------- | -------- | ----------------------------------------------------- |
| `PB_VERSION` | No       | `0.36.8` | PocketBase version downloaded during the image build. |

## Environment variables

| Variable | Required | Default | Description                                                          |
| -------- | -------- | ------- | -------------------------------------------------------------------- |
| `PORT`   | No       | `8080`  | Port used by PocketBase. Railway usually injects this automatically. |
