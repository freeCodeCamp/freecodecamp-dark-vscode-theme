## How to work on the extension:
- Fork and clone the repo to your computer
- Go to the repo folder in the terminal and open it with `code .`
- Make your changes, set a new version in `package.json` if your are making changes to the theme that need to be published
- Press `f5` to open the extension in a new VS Code window to see your changes
- Make a PR

## Reviewing PR's
- Checkout the PR
- Test the changes
- If intending to publish, the version in `package.json` will need to be new
- Merge it if it looks good

## How to publish the extension:
- Make sure you are on the latest `main` branch of the repo
- You will need to be given access to publish from the publisher account owner
- Install the `vsce` command with `npm install -g vsce` if you don’t have it
- Log in to the freeCodeCamp publisher account with `vsce login freeCodeCamp`, you will be prompted for your personal access token. If you don't have one, follow the [instructions here](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#get-a-personal-access-token) to create one. Make sure you use your email@freeCodeCamp.org account
- Run `vsce package` to create the `.vsix` file
- Run `vsce publish` to publish the new version
