# Updating the Version

1. Update `package.json` version number
2. `npm run version` to update the manifest and version file
3. Commit changes
4. `npm run version:github` commits the version number tag to the repo and pushes it, which kicks the GitHub action to prepare the release.
