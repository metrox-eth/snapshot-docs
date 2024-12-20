---
description: >-
  Learn how you can submit your vote on a proposal and how your voting power is
  calculated.
---

# Vote on a proposal

## Who can vote on proposals?

There are several aspects that define if you are eligible to vote on a specific proposal.&#x20;

### Voting strategies

Each space specifies their [voting strategies](../voting-strategies.md) in the [space settings.](../spaces/settings.md#voting-strategies) You can see the custom setup by opening the space settings. This setup can define if you are eligible to take part in the voting and what is your voting power calculated at the [snapshot of proposal creation](../create.md#snapshot-block-number).

In most cases you will be required to have a sufficient amount of tokens in the connected wallet at the time of proposal creation. One of the most common questions we receive on our support channels is [**Why can't I vote?**](https://github.com/snapshot-labs/snapshot/discussions/767)&#x20;

More often than not the answer is - **you did not hold the sufficient amount of specified token at the time of proposal creation.**

### Voting validation

Another aspect determining whether you are eligible to vote or not is a [voting validation](../validation-strategies.md) defined by the space. It is a mechanism used to define certain conditions like minimum token balance or also to prevent [Sybil Attacks](https://en.wikipedia.org/wiki/Sybil_attack). In other words the space owner wants to make sure that you are human and that bot or fake accounts are not used to overrule the outcome of the voting.&#x20;

## Cast a vote

1. Click the `Connect wallet` button in the top right corner.
2. Connect with the wallet provider where you hold the tokens relevant for the space you want to vote in.
3. Go to the space page on Snapshot and selected the active proposal you are interested in.
4. Select the option(s) you want to vote for. The [voting systems](../../proposals/voting-types.md) can differ between individual proposals.
5. Click to `Vote` button and sign the message via your wallet provider when prompted.&#x20;
6. Voilà! You have casted a vote :tada:

{% hint style="info" %}
If you are using MetaMask you'll need to scroll to the end of the signature and click on the arrow down for the Sign button to become active.\
\
Voting on Snapshot doesn't affect your account or the funds that are associated to it.
{% endhint %}
