# Issue Triage Guidelines

## Purpose

Speed up issue management.

The `etcd` issues are listed at https://github.com/etcd-io/etcd/issues
and are identified with labels. For example, an issue that is identified
as a bug will eventually be set to label `area/bug `. New issues will
start out without any labels, but typically `etcd` maintainers and active contributors
add labels based on their findings. The detailed list of labels can be found at
https://github.com/kubernetes/kubernetes/labels

Following are few predetermined searches on issues for convenience:
* [Bugs](https://github.com/etcd-io/etcd/labels/area%2Fbug)
* [Help Wanted](https://github.com/etcd-io/etcd/labels/Help%20Wanted)
* [Longest untriaged issues](https://github.com/etcd-io/etcd/issues?utf8=%E2%9C%93&q=is%3Aopen+sort%3Aupdated-asc+)

## Scope

These guidelines serves as a primary document for triaging an incoming issues in
`etcd`. Everyone is welcome to help manage issues and PRs but the work and responsibilities discussed in this document are created with `etcd` maintainers and active contributors in mind.

## Validate if an issue is a bug

Validate if the issue is indeed a bug. If not, add a comment with your findings and
close trivial issue. For non-trivial issue, wait to hear back from issue reporter and see if there is any
objection. If you don't hear from issue reporter in 30 days, close the issue.

##Inactive issues

Issues that lack enough information from the issue reporter should be closed if issue reporter do not provide information in 60 days.

## Duplicate issues

If an issue is a duplicate, add a comment stating so along with a reference for the original issue and close it.

## Issues that don't belong to etcd

Sometime issues are reported that actually belongs to other projects that `etcd` use. For example, `grpc` or `golang` issues. Such issues should be addressed by asking reporter to open issues in appropriate other project. Close the issue unless you and issue reporter see a need to keep it open for tracking purpose.

## Verify important labels are in place

Make sure that issue has label on areas it belongs to, proper assignees are added and milestone is identified. If any of these labels are missing, you can add one if you are authorized to do so. If you can not assign labels or you can not decide the correct label, that’s fine, contact technical leaders of the SIG to do so.

## Poke issue owner if needed

If you see any issue which is owned by a developer but a PR is not created in 30 days, you should contact the issue owner and ask for a PR or to release ownership if needed.
