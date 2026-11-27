---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: companies, other legal entities, and/or qualified and professional investors registered and approved to use the Platform
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons or territories
    text: It is neither incorporated, nor based nor operating from a territory which is subject to sanctions imposed by Switzerland, the European Union, or the United States of America
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: OBLIGATE is conducting a KYC & KYB process. Only Users approved by OBLIGATE may use the Platform and the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Obligate
provenance_date: '2026-11-10'
provider_name: Obligate
provider_slug: obligate
slug: obligate-eligibility
source_date: '2026-11-10'
source_filename: obligate-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/63a02e47caead88db4be659f/6a465cc535b5fa553a28bf1c_240315_Obligate%20General%20Terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Obligate\naid: obligate\nurl: https://cdn.prod.website-files.com/63a02e47caead88db4be659f/6a465cc535b5fa553a28bf1c_240315_Obligate%20General%20Terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: companies, other legal entities, and/or qualified and professional investors registered and approved to\n    use the Platform\nrestricted_uses:\n- summary: Sanctioned persons or territories\n  text: It is neither incorporated, nor based nor operating from a territory which is subject to sanctions imposed\n    by Switzerland, the European\
  \ Union, or the United States of America\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: OBLIGATE is conducting a KYC & KYB process. Only Users approved by OBLIGATE may use the Platform and the\n    Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/obligate/eligibility/obligate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Obligate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Securities
- Tokenization
- Blockchain
- Debt Capital Markets
- Private Credit
- Bonds
- Real World Assets
- Trade Finance
- Fintech
---
