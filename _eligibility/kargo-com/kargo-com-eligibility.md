---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to this Web Site content or materials from jurisdictions where such access is illegal is strictly prohibited.
  entity_types:
  - text: for personal, non-commercial transitory viewing only
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: use the materials for any commercial purpose
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
name: Kargo
provenance_date: '2026-11-09'
provider_name: Kargo
provider_slug: kargo-com
slug: kargo-com-eligibility
source_date: '2026-11-09'
source_filename: kargo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.kargo.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kargo\naid: kargo-com\nurl: https://www.kargo.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to this Web Site content or materials from jurisdictions where such access is illegal is strictly\n    prohibited.\nentity_types:\n- type: individual\n  text: for personal, non-commercial transitory viewing only\nrestricted_uses:\n- summary: No commercial use\n  text: use the materials for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kargo-com/eligibility/kargo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kargo's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Media
- Technology
- Marketing
- Platform
- Company
---
