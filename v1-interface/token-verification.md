---
description: Learn how to verify a token for your Space.
---

# Token verification

## What are verified tokens?

Verified tokens refer to tokens that have been **officially verified and listed** on specific platforms or curated lists. These lists, such as the [Ethereum](https://tokenlists.org/token-list?url=https://tokens.coingecko.com/uniswap/all.json), and [Polygon](https://api-polygon-tokens.polygon.technology/tokenlists/polygonTokens.tokenlist.json), serve as trusted sources that confirm the validity and authenticity of tokens within the respective blockchain ecosystems.

Snapshot is using the [Uniswap](https://tokenlists.org/token-list?url=https://tokens.coingecko.com/uniswap/all.json) list in combination with Snapshot's own list in order to verify assets available for building transactions.

By default tokens that are on the list are marked as verified with a green badge:

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

To see unverified tokens you can select the filter option:

<figure><img src="../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

## Adding a verified token to Snapshot's list

### 1. Create a fork&#x20;

Fork the snapshot-sidekick repository on Github:

{% @github-files/github-code-block url="https://github.com/snapshot-labs/snapshot-sidekick" %}

### 2. Update the token list file

Navigate to `data/verifiedTokens.json` file:

```
└── data
    └── verifiedTokens.json
```

Update it with the JSON details of the token you wish to add (replace each value accordingly):

```
{
  "name": "Wrapped Ether",
  "address": "0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6",
  "symbol": "WETH",
  "decimals": 18,
  "chainId": 5,
  "logoURI": ""
}
```

{% hint style="info" %}
Make sure to keep structure of the file intact and add necessary commas before or after the curly braces`{}.`
{% endhint %}

### 3. Create a Pull Request

If all the details are correct create a new PR on the original [snapshot-sidekick](https://github.com/snapshot-labs/snapshot-sidekick) repo.

### 4. Wait for the team to approve the PR

It's now in the hands of the Snapshot team to review your changes and apply them to [https://snapshot.org](https://snapshot.org).&#x20;

The average time to merge a PR is 2-3 days, so please be patient! 😉
