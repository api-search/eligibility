---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you use this Site outside the United States of America, you are responsible for following applicable local laws.
  minimum_age:
    text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any information to the Company or the Site.
    value: '13'
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
name: TypeLaw
provenance_date: '2026-11-10'
provider_name: TypeLaw
provider_slug: typelaw
slug: typelaw-eligibility
source_date: '2026-11-10'
source_filename: typelaw-eligibility.yml
source_heading: Eligibility
source_page: https://www.typelaw.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TypeLaw\naid: typelaw\nurl: https://www.typelaw.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you use this Site outside the United States of America, you are responsible for following applicable\n    local laws.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any\n    information to the Company or the Site.\n"
source_yaml_url: https://artifacts.apis.io/typelaw/eligibility/typelaw-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from TypeLaw's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Document Automation
- Court Filings
- Briefs
- Artificial Intelligence
---
