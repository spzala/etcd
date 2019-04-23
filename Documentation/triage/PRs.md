# PR Management

## Purpose

Speed up PR management.

The `etcd` PRs are listed at https://github.com/etcd-io/etcd/pulls 
A PR can have various labels, milestone, reviewer etc. The detailed list of labels can be found at 
https://github.com/kubernetes/kubernetes/labels

Following are few example searches on PR for convenience:
* [Open PRS for milestone etcd-v3.4](https://github.com/etcd-io/etcd/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aopen+milestone%3Aetcd-v3.4)
* [PRs under investigation](https://github.com/etcd-io/etcd/labels/Investigating)

## Scope

These guidelines serves as a primary document for managing PRs in `etcd`. Everyone is welcome to help manage PRs but the work and responsibilities discussed in this document is created with `etcd` maintainers and active contributors in mind.

## Handle inactive PRs
Poke issue owner if review comments are not addressed in 15 days. If you do not hear back from the PR owner in 90 days, you should update the PR as a new commit if possible. If not, inactive PR should be closed after 180 days.

## Poke reviewer if needed

Reviewers are responsive in a timely fashion, but considering everyone is busy, give them some time if you ask for review and do not get a quick response. If you do not get a response in 7 days, you should contact them via adding a comment in the PR or sending an email or message on the Slack.

## Verify important labels are in place

Make sure that appropriate reviewers are added to the PR. You should also make sure that milestone is identified. If any of these or other important labels are missing, you should add them. If you can not decide the correct label, leave a comment for the maintainers of the SIG to do so if needed.
