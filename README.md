# Example repo using the `sipfront/action-call-test` GitHub Workflow Action

Sipfront is a test automation platform for telecom tests.
It is hosted at [https://app.sipfront.com](https://app.sipfront.com),
and you can find more information on our [homepage](https://sipfront.com).

This repository demonstrates the integration of a Sipfront end-to-end call test
into the GitHub CI/CD pipeline.

## Run the demo

1. Fork this repository
1. Simulate a code change by running `date >> src/testfile.txt`
1. Commit and push the changes
1. Create a pull request to merge your change into upstream (this) repository

After creating the pull request, you will see the Sipfront test running in
the background, and eventually you'll get a green checkmark or a red cross
indicating the test result.

## Integrate Sipfront tests into your own repo

Copy the [example workflow YAML file](https://github.com/sipfront/github-action-examples/blob/master/.github/workflows/run_sipfront_on_pr.yml) to your own repository, and adapt it as needed.

You can find the documentation for setting up the workflow and its prerequisites in the
[action documentation](https://github.com/marketplace/actions/sipfront-call-test).

**IMPORTANT:** You need to set up the Sipfront API credentials in the repository secrets,
please read the docs!








