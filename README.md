# Orb Project Template

[![CircleCI Build Status](https://circleci.com/gh/fluidshare/app-tools.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/fluidshare/app-tools) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/fluidshare/app-tools)](https://circleci.com/orbs/registry/orb/fluidshare/app-tools) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/fluidshare/app-tools/main/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/fluidshare/app-tools) - The official registry page of this orb for all versions, executors, commands, and jobs described.

## Contributing

We welcome [issues](https://github.com/fluidshare/app-tools/issues) to and [pull requests](https://github.com/fluidshare/app-tools/pulls) against this repository!

## Publishing

* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from fore _feature branch_ to `main`.
* The title of the pull request must contain a special semver tag: `[semver:<segement>]` where `<segment>` is replaced by one of the following values.

| Increment | Description|
| ----------| -----------|
| major     | Issue a 1.0.0 incremented release|
| minor     | Issue a x.1.0 incremented release|
| patch     | Issue a x.x.1 incremented release|
| skip      | Do not issue a release|

Example: `[semver:major]`

* Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
* On merge, after manual approval, the orb will automatically be published to the Orb Registry.

For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).
