# Awesome GitHub Actions [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![DOI](https://zenodo.org/badge/1010869955.svg)](https://doi.org/10.5281/zenodo.19673356) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of high-quality resources, actions, tools, and workflows for [GitHub Actions](https://github.com/features/actions) – GitHub's powerful CI/CD and automation platform.

GitHub Actions enables you to automate tasks across the software development lifecycle. This list is intended for developers, DevOps engineers, and open-source maintainers.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [Community Guides & Tutorials](#community-guides--tutorials)
- [Popular GitHub Actions](#popular-github-actions)
- [CI/CD Workflows](#cicd-workflows)
- [Security](#security)
- [Testing](#testing)
- [Deployment](#deployment)
- [Linting & Code Quality](#linting--code-quality)
- [Automation](#automation)
- [Tools & Utilities](#tools--utilities)
- [Templates & Boilerplates](#templates--boilerplates)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions) – Official GitHub Actions documentation and getting started guides.
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions) – Explore reusable actions from the community.
- [Learning Lab: GitHub Actions](https://lab.github.com/githubtraining/github-actions:-hello-world) – Interactive course for getting started.

## Community Guides & Tutorials

- [GitHub Actions by Example](https://github-actions.byexamples.dev/) – Real-world examples and patterns.
- [Awesome Actions Examples (GitHub repo)](https://github.com/sdras/awesome-actions) – Community-curated list of actions and examples.
- [Introduction to GitHub Actions](https://www.taniarascia.com/github-actions/) – Beginner-friendly overview and tutorial.

## Popular GitHub Actions

- [actions/checkout](https://github.com/actions/checkout) – Checkout your repository under `$GITHUB_WORKSPACE`.
- [actions/setup-node](https://github.com/actions/setup-node) – Setup Node.js for your workflow.
- [actions/setup-python](https://github.com/actions/setup-python) – Setup Python with version support and caching.
- [docker/build-push-action](https://github.com/docker/build-push-action) – Build and push Docker images with BuildKit support.
- [JamesIves/github-pages-deploy-action](https://github.com/JamesIves/github-pages-deploy-action) – Deploy to GitHub Pages.
- [game-ci/unity-builder](https://github.com/game-ci/unity-builder) – Build Unity projects for multiple target platforms using GitHub Actions.

## CI/CD Workflows

- [CI/CD Templates (GitHub)](https://github.com/actions/starter-workflows) – Official GitHub starter workflows.
- [Node.js CI](https://docs.github.com/en/actions/publishing-packages/publishing-nodejs-packages) – CI for Node.js projects and npm publishing.
- [Python CI Template](https://github.com/actions/starter-workflows/blob/main/ci/python-package.yml) – Run tests and lint for Python packages.

## Security

- [GitHub Code Scanning](https://docs.github.com/en/code-security/code-scanning) – Scan your codebase for vulnerabilities.
- [trilom/file-changes-action](https://github.com/trilom/file-changes-action) – Detect file changes across branches or PRs.
- [GitLeaks Action](https://github.com/gitleaks/gitleaks-action) – Scan repositories for secrets and keys.

## Testing

- [Setup Test Coverage with Codecov](https://github.com/codecov/codecov-action) – Upload coverage reports to Codecov.
- [setup-java](https://github.com/actions/setup-java) – Setup Java and run Maven/Gradle builds.
- [cypress-io/github-action](https://github.com/cypress-io/github-action) – Run Cypress end-to-end tests.

## Deployment

- [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages) – Deploy static sites to GitHub Pages.
- [appleboy/ssh-action](https://github.com/appleboy/ssh-action) – SSH to remote servers and run commands.
- [firebase/actions-hosting-deploy](https://github.com/firebase/actions-hosting-deploy) – Deploy to Firebase Hosting.

## Linting & Code Quality

- [github/super-linter](https://github.com/github/super-linter) – All-in-one linter supporting multiple languages.
- [reviewdog/action-eslint](https://github.com/reviewdog/action-eslint) – Run ESLint and add comments to pull requests.
- [peter-evans/create-pull-request](https://github.com/peter-evans/create-pull-request) – Automate code formatting and create pull requests with changes.

## Automation

- [stale](https://github.com/actions/stale) – Automatically mark and close stale issues and pull requests.
- [assign-reviewers](https://github.com/hmarr/auto-assign-action) – Automatically assign reviewers to new pull requests.
- [release-drafter](https://github.com/release-drafter/release-drafter) – Automate changelog generation and draft releases.

## Tools & Utilities

- [llms-txt-generator](https://github.com/thedarkbeet/llms-txt-generator) – Zero-dependency CLI and GitHub Action that generates `llms.txt` manifest files for websites and repos.
- [act](https://github.com/nektos/act) – Run GitHub Actions locally for faster development and debugging.
- [workflow-dispatch](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#workflow_dispatch) – Manually trigger workflows via GitHub UI or API.
- [cache](https://github.com/actions/cache) – Cache dependencies and build outputs for faster workflows.

## Templates & Boilerplates

- [actions/starter-workflows](https://github.com/actions/starter-workflows) – Official GitHub Action templates for different languages and frameworks.
- [ci-cd-github-actions-examples](https://github.com/vemel/ci-cd-github-actions-examples) – Real-world CI/CD workflow examples for common project setups.

## Related Awesome Lists

- **[Awesome CI](https://github.com/awesomelistsio/awesome-ci)** – Continuous Integration tools and services.
- **[Awesome DevOps](https://github.com/awesomelistsio/awesome-devops)** – DevOps tools, platforms, and resources.
- **[Awesome Automation](https://github.com/awesomelistsio/awesome-automation)** – Automation tools and frameworks across use cases.
  
## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
