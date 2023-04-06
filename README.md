# clean-typescript

This is a simple typescript template repo for getting started.  Start coding index.ts.  Tooling uses:

- `tsc` for building
- `jest` for testing
- `npm` for versioning
- `.github/workflows` (i.e github actions) for automation

If you want to release to npm you can release with the button in github and the github actions will ship it to npm.

## To Do with a new repo

- [ ] Update the package.json with the correct repo and name
- [ ] Publish to npm for the first time. Doing it locally with `npm publish --access=public` is probably easiest
- [ ] Clear template info for readme and update with better info 

## In your repo, delete above this and carry on with your new repo ^^^

# <New Repo Title Here>

## Getting Started

- `npm run test` - Runs the test runner
- `npm run build` - Builds using `tsc` from configs in the `tsconfig.json`
- `npm run dev` - Runs build and watches

#### Versioning

These commands should be run from the master branch when ready to bump a version.
Bumping a version will commit the bump and push it up as long as pushing tags up for release.

- `npm run v-bump` - Bumps current version i.e. `1.2.4` would bump to `1.2.5`
- `npm run v-minor-bump` - Bumps Minor version i.e. `1.2.4` would bump to `1.3.0`
- `npm run v-major-bump` - Bumps current version i.e. `1.2.4` would bump to `2.0.0`
