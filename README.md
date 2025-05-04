# Core Approve PR Action

[![License](http://img.shields.io/badge/license-mit-blue.svg?style=flat-square)](https://raw.githubusercontent.com/securefix-action/core-approve-pr-action/main/LICENSE) | [Versioning Policy](https://github.com/suzuki-shunsuke/versioning-policy/blob/main/POLICY.md)

`Core Approve PR Action` is a set of components of [Approve PR Action](https://github.com/securefix-action/approve-pr-action).

This composes of following actions:

- [parse-label](parse-label/action.yaml): Parse a label description and output a pull request repository and number
- [validate](validate/action.yaml): Validate if the pull request should be approved
- [request](request/action.yaml): Create a label to send a request to a server workflow
- [approve](approve/action.yaml): Approve a pull request
- [notify](notify/action.yaml): Notify a failure to a pull request
