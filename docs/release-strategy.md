# Release Strategy

This is the process for publishing a change to the NPM registry:

1. Make changes as part of PR
2. Once merged into `main` create tags for whichever package(s) changed:
   * `git tag genesys-web-messaging-tester-vX.X.X`
   * `git tag genesys-web-messaging-tester-cli-vX.X.X`
3. Using GitHub's UI create a Release based on the most recent tag

_If a merged PR increased the version of both packages then create the two tags
(following the format in the step above) then create a release off of the
tag created last._