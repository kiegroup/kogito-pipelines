# Kiegroup Kogito organization repositories CI Status

This project is based on [chain-status](https://github.com/kiegroup/chain-status) and information generated thanks to [build-chain-configuration-reader](https://github.com/kiegroup/build-chain-configuration-reader) using [kogito-pipelines definition file](https://github.com/kiegroup/kogito-pipelines/blob/main/.ci/pull-request-config.yaml).

Due to the retrieved information requires a `GITHUB_TOKEN` and github API has a limitation it is better to not collect the information on every request from this webpage is made. So this webpage does not really requires an application service and all the required data is stored in github pages. This information is normally retrieved, treated and stored using [chain-status/action tool](https://github.com/kiegroup/chain-status/tree/main/packages/action) which is exposed as a Github Action tool, so we can customize the job execution frequency as we need.
