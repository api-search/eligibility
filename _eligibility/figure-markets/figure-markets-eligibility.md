---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Crypto loans are offered to U.S. borrowers by Figure Lending LLC.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Crypto-backed loans unavailable in certain states
    text: This product is not available to U.S. residents of DC, ID, IL, KY, MD, MS, SD, TX, VT, or VA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Figure Markets
provenance_date: '2026-11-09'
provider_name: Figure Markets
provider_slug: figure-markets
slug: figure-markets-eligibility
source_date: '2026-11-09'
source_filename: figure-markets-eligibility.yml
source_heading: Eligibility
source_page: https://www.figuremarkets.com/disclosures/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Figure Markets\naid: figure-markets\nurl: https://www.figuremarkets.com/disclosures/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Crypto loans are offered to U.S. borrowers by Figure Lending LLC.\nentity_types: []\nrestricted_uses:\n- summary: Crypto-backed loans unavailable in certain states\n  text: This product is not available to U.S. residents of DC, ID, IL, KY, MD, MS, SD, TX, VT, or VA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/figure-markets/eligibility/figure-markets-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Figure Markets's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- Digital Assets
- Exchange
- Trading
- Blockchain
- Lending
- Stablecoins
- Provenance Blockchain
---
