## How to work on the extension:
- Fork and clone the repo to your computer
- Go to the repo folder in the terminal and open it with `code .`
- Make your changes, including changing the version in `package.json`
- Press `f5` to open the extension in a new VS Code window to see your changes
- Make a PR

## Reviewing PR's
- Checkout the PR
- Make sure there's a new version in the `package.json`
- Test the changes
- Merge it if it looks good

## How to publish the extension:
- You will need the `vsce` command. Install it with `npm install -g vsce` if you don’t have it
- Log in to the freeCodeCamp account with `vsce login freeCodeCamp-org`, you will be prompted for the personal access token
- Run `vsce package` to create the `.vsix` file
- Run `vsce publish` to publish the new version
