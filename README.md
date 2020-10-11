# Kubeval Orb Project

[![CircleCI Build Status](https://circleci.com/gh/kiddo3/kubeval-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/kiddo3/kubeval-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/kiddo3/kubevalorb)](https://circleci.com/orbs/registry/orb/kiddo3/kubevalorb) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/kiddo3/kubeval-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)



Tool to run kubeval in CircleCI.

Additional READMEs are available in each directory.



## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/kiddo3/kubeval-orb) - The official registry page of this orb for all versions, executors, commands, and jobs described.
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/kiddo3/kubeval-orb/issues) to and [pull requests](https://github.com/kiddo3/kubeval-orb/pulls) against this repository!

### How to Publish
* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from fore _feature branch_ to `master`.
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

### Kubeval repository

https://github.com/instrumenta/kubeval
