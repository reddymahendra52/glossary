---
title: Continuous Delivery (CD)
status: Completed
category: concept
---
## Continuous Delivery/Deployment (CD)

### What it is
Continuous delivery, often abbreviated as  CD, is a set of practices in which code changes are automatically deployed into an acceptance environment (or, in the case of continuous deployment, into production). CD crucially includes procedures to ensure that software is adequately tested before deployment and provides a way to rollback changes if deemed necessary. Continuous integration (CI) is the first step towards continuous delivery (i.e., changes have to merge cleanly before being tested and deployed).

### Problem it Addresses
Deploying [reliable](https://github.com/cncf/glossary/blob/main/definitions/reliability.md) updates becomes a problem at scale. Ideally, we'd deploy more frequently to deliver better value to end-users. However, doing it manually translates into high transaction costs for every change. Historically, to avoid these costs, organizations have released less frequently, deploying more changes at once and increasing the risk that something goes wrong.

### How it Helps
CD strategies create a fully automated path to production that tests and deploys the software using various deployment strategies such as [canary](https://github.com/cncf/glossary/blob/main/definitions/canary_deployment.md) or [blue-green](https://github.com/cncf/glossary/blob/main/definitions/blue_green_deployment.md) releases. This allows developers to deploy code frequently,  giving them peace of mind that the new revision has been tested. Typically, trunk-based development is used in CD strategies as opposed to feature branching or pull requests.


