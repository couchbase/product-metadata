# Notice

At time of writing, the files `apt.json` and `yum.json` are referenced by:

- [check_cowbuilder_distros](https://github.com/couchbase/build-infra/blob/master/docker/buildslaves/sdk/cowbuilder/jenkins/check_cowbuilder_distros.sh#L12)
- [couchbase-release](https://github.com/couchbase/build-tools/blob/681a3e3683d33218d4644ce037addf07dab61bfe/couchbase-release/go.sh#L33-L45)
- [repo_upload/apt](https://github.com/couchbase/build-tools/blob/681a3e3683d33218d4644ce037addf07dab61bfe/repo_upload/repo_upload/repos/apt.py#L41-L45)
- [repo_upload/yum](https://github.com/couchbase/build-tools/blob/681a3e3683d33218d4644ce037addf07dab61bfe/repo_upload/repo_upload/repos/yum.py#L49-L55)

Please make any updates necessary to the relevant scripts if you are changing the structure of the data in these files.
