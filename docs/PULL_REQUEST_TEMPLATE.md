If you'd like to request a chain to be supported by Sourcify, please follow this pull request template. Delete contents otherwise.

## Network Information

%%%%%%%%%

Please include a min 5-6 sentence information about your network here. What is it used for? What is the website? Is it fully EVM compatible or does it use a different compiler than the official Solidity compilers with custom opcodes etc? How are you planning to make use of the data provided by Sourcify?

%%%%%%%%%

## Checklist

- [ ] You didn't modify [chains.json](/services/core/src/chains.json) and the information there is correct.
- [ ] You added your network to [sourcify-chains.ts](services/core/src/sourcify-chains.ts), [constants.ts](ui/src/common/constants.ts), and [README](/README.md)
- [ ] You provided a test contract on your network with address, metadata, and source code.
- [ ] Introductory information about the network is added to this PR.
- [ ] The base branch is **staging** and not master.
