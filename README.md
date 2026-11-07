# Domain hacks One-Word Domains (1,458)

1,458 names in this list today, refreshed every night.

Live page: [unique.domains/domains/hacks](https://unique.domains/domains/hacks?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [hacks.csv](https://github.com/UniqueDomains/hacks-oneword-domains/raw/main/hacks.csv), 1,000 rows
- [hacks.json](https://github.com/UniqueDomains/hacks-oneword-domains/raw/main/hacks.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/hacks-oneword-domains/main/hacks.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain        | status    | purchase_price | renewal_price | attractiveness | demand | length |
| ------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| selfportra.it | available | $6.60          | $5.45         | high           | low    | 13     |
| sibl.ing      | premium   | $672.95        | $672.95       | high           | low    | 7      |
| blacki.sh     | available | $39.99         | $47.99        | high           | low    | 8      |
| blast.ing     | premium   | $3,000.20      | $3,900        | high           | low    | 8      |
| trimm.ing     | premium   | $150.20        | —             | high           | low    | 8      |
| falte.red     | available | $8.48          | $18.83        | low            | low    | 8      |
| shap.ing      | premium   | $845           | $845          | high           | low    | 7      |
| plann.ing     | premium   | $3,105.20      | $3,105.20     | high           | medium | 8      |
| pulsebe.at    | available | $10.99         | $10.99        | high           | low    | 9      |
| chas.ing      | premium   | $1,300.20      | $1,690        | high           | low    | 7      |
| dog.fish      | resell    | —              | —             | high           | low    | 7      |
| griev.ing     | premium   | $90.20         | $112.50       | medium         | low    | 8      |
| bloods.hot    | available | $41.60         | $41.60        | medium         | low    | 9      |
| uninju.red    | available | $9.48          | $28.48        | high           | low    | 9      |
| f.law         | resell    | —              | —             | high           | low    | 4      |
| undulat.us    | available | $6.50          | $6.50         | high           | low    | 9      |
| undy.ing      | premium   | $90.20         | $112.50       | medium         | low    | 7      |
| moorga.me     | available | —              | —             | high           | high   | 8      |
| comput.ing    | premium   | $3,105.20      | $3,105.20     | high           | high   | 9      |
| bless.ing     | premium   | $3,750         | $3,750        | high           | low    | 8      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 1,458 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, Domain hacks One-Word Domains, https://unique.domains/domains/hacks, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_hacks_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

Questions and corrections: `kai@unique.domains`
