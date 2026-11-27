---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: are legal residents in the United Kingdom.
  entity_types:
  - text: Unless otherwise provided in the Experience Rules, Prize Draws are only open to individuals who at the time of entry to a Prize Draw
    type: individual
  minimum_age:
    text: are at least 18 years of age
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Omaze may require Participants to provide documentary evidence (e.g. copy of a passport, driving licence or recent utility bill) to verify their eligibility.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Omaze
provenance_date: '2026-11-10'
provider_name: Omaze
provider_slug: omaze
slug: omaze-eligibility
source_date: '2026-11-10'
source_filename: omaze-eligibility.yml
source_heading: Eligibility
source_page: https://omaze.co.uk/pages/legal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omaze\naid: omaze\nurl: https://omaze.co.uk/pages/legal-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: are legal residents in the United Kingdom.\nentity_types:\n- type: individual\n  text: Unless otherwise provided in the Experience Rules, Prize Draws are only open to individuals who at the time\n    of entry to a Prize Draw\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Omaze may require Participants to provide documentary evidence (e.g. copy of a passport, driving licence\n    or recent utility bill)\
  \ to verify their eligibility.\nminimum_age:\n  value: '18'\n  text: are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/omaze/eligibility/omaze-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Omaze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Charity
- Fundraising
- Non-Profit
- Prize Draws
- Sweepstakes
- E-Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
- United Kingdom
- Germany
---
