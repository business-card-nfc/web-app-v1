# Deployment environment

## Development

1. Open the folder in a VS Code dev container

https://github.com/business-card-nfc/web-app-v1/blob/2708e85956f6e7e553754107a54f52b3d75693ca/.devcontainer/devcontainer.json#L1-L23

2. Run `./vendor/bin/sail up`

## Production

1. `git push` to main branch
2. Visit https://dashboard.heroku.com/apps/business-card-nfc-web-app-v1/deploy/github