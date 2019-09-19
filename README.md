# Terraform Orb [![CircleCI Build Status](https://circleci.com/gh/titel-media/terraform-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/titel-media/terraform-orb)

A Terraform Orb for CircleCI.
It allows you to interact with Terraform from within a CircleCI build job.


## Prerequisites

The following environment variables need to be set in CircleCI either directly or via a context:

- GOOGLE_CREDENTIALS (required)

See [CircleCI Documentation](https://circleci.com/docs/2.0/env-vars) for instructions on how you would set this up.


## Usage

Example use as well as a list of available executors, commands, and jobs are available on this orb's [registry page][reg-page].


## Resources

[CircleCI Orb Registry Page][reg-page] - The registry page for this orb with all versions, executors, commands, and jobs described.
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.
[Terraform by HashiCorp (TF) Docs](https://www.terraform.io/docs/index.html) - General docs for Terraform.


## Contributing
We welcome [issues](https://github.com/titel-media/terraform-orb/issues) to and [pull requests](https://github.com/titel-media/terraform-orb/pulls) against this repository!
For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/ecosystem/orbs).

### Publishing

New versions of this orb are published by pushing a SemVer git tag by the Community & Partner Engineering Team.

[reg-page]: https://circleci.com/orbs/registry/orb/titel-media/terraform
