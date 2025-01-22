# discussionator

This is a tool to interface with Github discussions via their CLI.

This tool is built-for-specific-purpose, so probably doesn't support what you need it to do.

## Sketch

The CLI does not support Discussions natively, but does support the GraphQL API, which does have Discussions support.
An example for viewing is provided [here](https://github.com/cli/cli/discussions/4212), but it is relatively unfriendly. We can extract the idea from that, and build a query generator that stitches together the correct `gh api graphql ...` call from input parameters
