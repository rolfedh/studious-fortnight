# studious-fortnight

Vale is a command-line tool you use to check your content files for style issues.

As a technical writer at Red Hat, you can use this repo to your system to help you get started with using Vale.

This repo contains minimal instructions for installing and using Vale. For more information, see https://github.com/errata-ai/vale.

This repo includes the [`red-hat` style](red-hat.md), which complies with Red Hat's style requirements for technical documentation. It also include a `.vale.ini` file that configures Vale to use the `red-hat` style with your `.adoc` and `.md` content files.

## Get started using Vale and the `red-hat` style

1. [Install the Vale command line tool on your workstation](https://docs.errata.ai/vale/install).
2. `git clone` this repo to your local machine.
3. If you downloaded it, extract the files.
3. Copy the `.vale.ini` file and `.vale` directory from the repo to the root directory of your Red Hat documentation project.
4. In a terminal, run `vale` on one of your content files. For example:
```bash
$ cd openshift-docs
$ vale modules/<filename>.adoc
```


## Benefits of using Vale

How does Vale help you improve your content quality and productivity?

* It helps you catch and fix style issues right away.
* It makes content is easier to understand and localize.
* It improves peer reviews.
* It makes content more consistent.

## Vale styles and rules

* A _style_ is a simple directory that contains a collection of rules.
* A _rule_ is a `.yml` file that defines the issue, the solution, and other information.
* You can use a style as-is, or you customize the rules it contains to fit your needs.
* This repo includes
// A _vocabulary_ is a simple directory that contains a collection of rules about your organization's

* You can download [various ready-to-use styles from Vale](https://github.com/errata-ai/styles), including ones based on the IBM, Google, and Microsoft style guides.

## Optional next steps

* [Install VS Code](https://code.visualstudio.com/docs/?dv=linux64_rpm) on your system, and install the [Vale plugin for VS Code](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server).
* [Add Vale to your docs continuous integration (CI) service](https://docs.errata.ai/vale/install#using-vale-with-a-continuous-integration-ci-service).
* [Add Vale to your GitHub actions](https://github.com/errata-ai/vale-action).

## How to get involved, get help, and contribute

* See the [Troubleshooting common errors](troubleshooting-common-errors.md) topic.
* Join the Slack channel, [#vale-at-red-hat](https://coreos.slack.com/archives/C0218RXJK5E), in the CoreOS workspace.
* To report a bug _in this repo_ or request an enhancement, please mention it here: https://github.com/rolfedh/studious-fortnight/issues.
* To show appreciation and support for Joseph Kato's work on Vale, please consider making a donation: https://docs.errata.ai/vale/about#sponsors
