---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom. We do not represent that content available on or through our site is appropriate or available in other locations.
  entity_types:
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  - text: 'If you are a business user, please note that in particular, we will not be liable for: loss of profits, sales, business, or revenue'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use prohibited for site
    text: You agree not to use our site for any commercial or business purposes
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
name: MMOB
provenance_date: '2026-11-10'
provider_name: MMOB
provider_slug: mmob
slug: mmob-eligibility
source_date: '2026-11-10'
source_filename: mmob-eligibility.yml
source_heading: Eligibility
source_page: https://www.mmob.com/legal-pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MMOB\naid: mmob\nurl: https://www.mmob.com/legal-pages/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom. We do not represent that content available\n    on or through our site is appropriate or available in other locations.\nentity_types:\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\n- type: business\n  text: 'If you are a business user, please note that in particular, we will not be liable for: loss of profits,\n    sales, business,\
  \ or revenue'\nrestricted_uses:\n- summary: Commercial use prohibited for site\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mmob/eligibility/mmob-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from MMOB's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Embedded Finance
- API Integration
- Platform
---
