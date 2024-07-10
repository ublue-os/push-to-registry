# push-to-registry

A GitHub Action to push OCI images to a Docker registry.

The interface is inspired by the [redhat-actions/push-to-registry](https://github.com/redhat-actions/push-to-registry) action, but since this was missing a few key features (namely retries and pushing multiple compression formats), we have created our own implementation of it.

The ideal next steps would be to contribute these features upstream to the [redhat-actions/push-to-registry](https://github.com/redhat-actions/push-to-registry) action and forget this mess ever existed.  Looking at the activity on RedHat's repository, I doubt this will be happen anytime soon.

> [!WARNING]
> You may think the implementation of this action is overly complicated and difficult to follow.  You would be right.
> I wanted to get the API locked down as much as possible, and can fix the implementation bit-by-bit when time allows.
