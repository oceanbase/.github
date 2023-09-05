# Contributing Guidelines

English | [中文版](CONTRIBUTING_CN.md)

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The OceanBase community warmly welcomes every developer for document adjustments, text corrections, bug fixes, or new features, each one of which is a great contribute to the OceanBase community.

If you are not familiar with the contribution workflow of OceanBase community, please refer to the following. And you are welcome to raise an issue or pull request directly in this repository to help us improve this guideline.

## Contribution Workflow

### Prerequisites

Before submitting code to OceanBase community projects, you should first complete the following prerequisites.

#### 1. GitHub Account

Before you get started, you will need to [sign up](http://github.com/signup) for a GitHub user account.

#### 2. Code of Conduct

Please make sure to read and observe the [Code of Conduct](CODE_OF_CONDUCT.md).

#### 3. Contributor License Agreement

Before you can contribute to OceanBase, you will need to sign the [Contributor License Agreement](https://cla-assistant.io/oceanbase/oceanbase) via your GitHub account.

### Community Contribution Workflow

The workflow of contributing to OceanBase is based on GitHub and generally includes the following steps.

#### 1. Take an Issue

We use [issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) to track tasks and feedback on GitHub, and now we divide issue templates into following types: `Bug Report`, `Documentation Related`, `Enhancement`, `Feature Request` and `Question`. We also have labeled `help wanted` or `good first issue` for some issues that are suitable for novice developers. You can start with these issues to make your first contribution.

Before you start development on the project, we recommend you to raise an issue for the modification and discuss with the community. If there is an existing issue you interested in, you can reply to the issue and let the maintainer assign it to you.

#### 2. Fork the Repository

Fork the project on GitHub and clone your fork locally, see [GitHub docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo) for details.

#### 3. Commit Your Modification

For developers who want to contribute to OceanBase database kernel code, you can refer to the [development guide](https://github.com/oceanbase/oceanbase/blob/master/docs/README.md).

For developers who want to contribute to other projects of OceanBase community, you can follow the documentation in the repository.

You can also refer to our [documentation website](https://en.oceanbase.com/docs) for more information.

After the modification is complete, you need to use Git to commit and push it to your fork repository.

#### 4. Submit a Pull Request

Now the development branch of your fork contains the commits you made, you need to use that branch to submit a pull request. For detailed operations, please refer to [GitHub docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

There is a pull request template for repositories in the community, you need to fill it out correctly so that others can better review your pull request. For the title format, we recommend using the [conventional commits](https://www.conventionalcommits.org). If your pull request solves an existing issue, please use keywords such as `close #xxx` to link the issue in the body of the pull request. For details, please refer to [GitHub docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue).

#### 5. Code Review

After the pull request is submitted, other developers in the community will review it. Some repositories also have CI (continuous integration) processes for compiling, unit testing, etc. You need to pay attention to the CI results, and if errors occur, please fix them in time.

If you need to update the code corresponding to the pull request, please directly add a new commit to the corresponding branch, and push it to your fork repository, then the pull request will be automatically updated.

When the review is completed and the CI has passed, your pull request will be merged into the main repository. At this point, you have completed a contribution to the OceanBase community.

## Communication

Please feel free to contact to the [community](https://github.com/oceanbase/oceanbase#community).

We hold developer meetings regularly, you can subscribe this [issue](https://github.com/oceanbase/oceanbase/issues/1368) for updates.
