# fool-stash
A simple utility to fake green builds on Stash.

When a build fails, Stash notifier would have updated the commit in stash to reflect the failed build. To update this status, use the key <JENKINS_PROJECT>-<JENKINS_BASE_URL> eg: "TMA-PR-http:\\/\\/in2npdvdcspr1:8080\\/".

You can also add multiple green builds to a commit by changing the build.
