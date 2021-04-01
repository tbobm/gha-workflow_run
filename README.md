# Github Action workflow run event example

- Every commit triggers Build ([`.github/workflows/build.yml`][gh-build])
- Successful Build triggers Unit Test ([`.github/workflows/unit-tests.yml`][gh-unit-tests])
- Successful Unit Test triggers Deploy ([`.github/workflows/deploy.yml`][gh-deploy])

Corresponding documentation:

- [events-that-triggers-workflows#workflow\_run][event-workflow_run]
- [workflow\_run event][workflow_run]

[event-workflow_run]: https://docs.github.com/en/actions/reference/events-that-trigger-workflows#workflow_run
[workflow_run]: https://docs.github.com/en/developers/webhooks-and-events/webhook-events-and-payloads#workflow_run
[gh-build]: ./.github/workflows/build.yml
[gh-unit-tests]: ./.github/workflows/unit-tests.yml
[gh-deploy]: ./.github/workflows/deploy.yml
