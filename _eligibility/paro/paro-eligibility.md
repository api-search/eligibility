---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Paro may request documents to verify this information, such as a copy of your government-issued identification or photo or a billing statement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Paro
provenance_date: '2026-11-10'
provider_name: Paro
provider_slug: paro
slug: paro-eligibility
source_date: '2026-11-10'
source_filename: paro-eligibility.yml
source_heading: Eligibility
source_page: https://paro.ai/platform-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paro\naid: paro\nurl: https://paro.ai/platform-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Paro may request documents to verify this information, such as a copy of your government-issued identification\n    or photo or a billing statement.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paro/eligibility/paro-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Paro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Accounting
- Marketplace
- Talent
- Fractional CFO
- Bookkeeping
- Professional Services
- Artificial Intelligence
---
