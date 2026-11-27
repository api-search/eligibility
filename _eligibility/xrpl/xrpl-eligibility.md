---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any country to which the United States has embargoed goods or services
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited user content
    text: User Content that is unlawful, libelous, defamatory, obscene, pornographic, indecent, lewd, suggestive, harassing, threatening, abusive, inflammatory, fraudulent, false, misleading or otherwise objectionable
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
name: XRP Ledger
provenance_date: '2026-11-10'
provider_name: XRP Ledger
provider_slug: xrpl
slug: xrpl-eligibility
source_date: '2026-11-10'
source_filename: xrpl-eligibility.yml
source_heading: Eligibility
source_page: https://ripple.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XRP Ledger\naid: xrpl\nurl: https://ripple.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country to which the United States has embargoed goods or services\nentity_types: []\nrestricted_uses:\n- summary: Prohibited user content\n  text: User Content that is unlawful, libelous, defamatory, obscene, pornographic, indecent, lewd, suggestive,\n    harassing, threatening, abusive, inflammatory, fraudulent, false, misleading or otherwise objectionable\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xrpl/eligibility/xrpl-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from XRP Ledger's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- XRP
- Cryptocurrency
- DeFi
- Ledger
- Web3
---
