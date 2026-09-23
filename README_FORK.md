This is a soft fork of Helix editor with the intent of:

1. Ensure further development of the editor while the current maintainers don't have time to continue with it.
2. Always rebase against Helix proper so that it will always be easily diffed and possibly (partially) squashed back to the proper Helix when it reactivates.
3. Maintain an unstable version similar to Debian Unstable with some PRs included that are stalled or rejected.

There's no intention to create another editor nor benefit from this fork in any way.
So, there will be no donations/bounties (please instead consider donating to the Helix maintainers).

I'm aware how hard it is to maintain even a fork.
Therefore, I'd like to make the project such as to require minimal work possible to maintain it.

Here's the list of PRs included so far:

- [Add rainbow indentation guides by omentic](https://github.com/helix-editor/helix/pull/9951)
- [feat: vcs: support Jujutsu as a diff-provider by poliorcetics](https://github.com/helix-editor/helix/pull/12022)
- [Add indentation-based text objects by burke](https://github.com/helix-editor/helix/pull/14773)
- [Hide Commandline by erasin](https://github.com/helix-editor/helix/pull/11223)
- [Implemented find char with leap/easyMotion/flash style by yerlaser](https://github.com/helix-editor/helix/pull/14844)
- [Add 'tsrx' to file-types for ripple language by yerlaser](https://github.com/helix-editor/helix/pull/16229)

Also included is my (yerlaser) workaround for enabling dot to be remapped.
