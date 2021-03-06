# Contributing

Howdy! Thanks for your interest in contributing to this project.

We adhere to the [Open Code of Conduct][code-of-conduct]. By
participating, you are expected to honor this code.

[code-of-conduct]: http://todogroup.org/opencodeofconduct/#OpenTable/opensource@opentable.com

### Reporting Issues
If you want to submit a bug report, [open a new issue][new-issue].
Please provide a detailed description of the issue and include any relevant
reproduction steps or stack traces.

[new-issue]: ../../issues/new

### Submitting Pull Requests
So you've decided you want to send us some code. That's awesome. No,
really, thank you.

To get you started, we put together this handy-dandy guide to submitting
your patch:

0. [Fork][] and clone the repository
0. Configure and install the dependencies: `script/bootstrap`
0. Make sure the tests pass on your machine: `script/test`
0. Create a new feature branch: `git checkout -b my-awesome-patch`
0. Make your change, add tests, and make sure the tests still pass
0. Add a CHANGELOG entry detailing your changes
0. Push to your fork and [submit a pull request][pr]
0. :beers:

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the style guide (see below) where possible.
- Write tests.
- Update documentation as necessary.
- Keep your change as focused as possible. If there are multiple changes you
would like to make that are not dependent upon each other, consider submitting
them as separate pull requests.
- Squash multiple commits into a single, clean commit.

[fork]: ../../fork
[pr]: ../../compare

### Style Guide
> This section should be modified on a per-project basis. Different teams,
> projects, and languages are going to have different style concerns. Your
> team should complete this section as a part of the OSS release process.

### Releasing
This section is for the project's maintainers.

- Use SemVer. Breaking the API in a non-backwards compatible way? Make sure
you version it properly. Details at http://semver.org/.
- Use Git tags for generating new releases. Generally tagging with the targeted
release version is acceptable.
