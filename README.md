# Open Ordinals Collections List

Crowsdourced list of Ordinals Collections for general use. This list was originally created for [bitcoin.museum](https://bitcoin.museum)

## Add a new collection

1. Add the collection metadata to `collections.json`

The format should be as follows:

```javascript
	{
		"collectionName": "Bitcoin Punks", //name
        "logo": "", //image that represents collection
		"twitter": "https://twitter.com/bitcoin_punks_", //twitter if any
		"website": "https://bitcoinpunks.com", //official project website
		"description": "", //description of the project
		"discord": "https://discord.gg/XTTqyTPsUg", //discord
		"lowestInscription": 89, //the lowest inscription number in the col
		"highestInscription": 34399, //highest inscription number in the col
		"totalSupply": 10000, //supply
		"idsFileSlug": "bitcoin-punks" //the name of the file with the ids that belongs to this collection
	}
```

2. Create a JSON file named after your collection (ie `bitcoin-punks.json`) in `/collections` with an array of inscription ids.

```json
[
	"665774e09f53f4570bfeb2aa82c5127131dae7dc163fa83914b12cbd30e49708i0",
	"66bffcc14b3845b30ab25570497d7f231c3f536561cc8a7aa97acdfc0e6cb8b9i0",
	"1d73acf27cdeb1452baabe2c6ee9704a0e580d922cda9de7e77771d29d78019fi0"
]
```

## Contribute

Initial data was added by me going through Twitter threads, discords and running random scripts.

If any info is wrong, please open a pull request and will try to verify and merge asap.
