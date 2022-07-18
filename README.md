# Community Blocklist

NFT Marketplaces like Mintgarden or dexie share this blocklist to hide affected NFTs or NFT collections.

## Use the Blocklist

A current exported blocklist is always available [here](https://raw.githubusercontent.com/dexie-space/blocklist/main/export/blocklist.json).

## Add an entry (Report)

You can use the reporting tool provided by dexie (link here soon) to report a DID or NFT collection. Alternatively add the affected DID to `dids/{did}.json` and create a pull request. The file should be in the following format:

```
{
  "did": "did:chia:1k74hq8jde9tve5vyyzw9vyy3alhvev792gchqdgsde8j9rg5u6ksfe35lc",
  "collectionId": "optional",
  "nftId": "optional",
  "reason": "impersonation",
  "date": "2022-07-18T10:05:18.177Z"
}
```

Please provide additional informations about your report in the description of the pull request.

## Remove an entry (Appeal)

To remove an entry, delete your DID from `dids/` and create a pull request. Please explain why your DID should be removed in the description of the pull request.
