---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is based in the United States. We make no claims concerning whether the Website and/or the Content may be viewed or be appropriate for use outside of the United States.
  entity_types:
  - text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to the Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive market research
    text: You will not access or use the Website to collect any market research for a competing businesses;
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
name: Malachyte
provenance_date: '2026-11-10'
provider_name: Malachyte
provider_slug: malachyte
slug: malachyte-eligibility
source_date: '2026-11-10'
source_filename: malachyte-eligibility.yml
source_heading: Eligibility
source_page: https://www.malachyte.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Malachyte\naid: malachyte\nurl: https://www.malachyte.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is based in the United States. We make no claims concerning whether the Website and/or the Content\n    may be viewed or be appropriate for use outside of the United States.\nentity_types:\n- type: business\n  text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that company or other legal entity to the Agreement\nrestricted_uses:\n- summary: Competitive\
  \ market research\n  text: You will not access or use the Website to collect any market research for a competing businesses;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/malachyte/eligibility/malachyte-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Malachyte's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Personalization
- Retail
- Real-Time
---
