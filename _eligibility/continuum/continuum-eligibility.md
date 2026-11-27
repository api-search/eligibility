---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are using the Site on behalf of a company or organization, that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful use
    text: Any unlawful, fraudulent, harmful, or unauthorized purpose.
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
name: Continuum
provenance_date: '2026-11-09'
provider_name: Continuum
provider_slug: continuum
slug: continuum-eligibility
source_date: '2026-11-09'
source_filename: continuum-eligibility.yml
source_heading: Eligibility
source_page: https://gocontinuum.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Continuum\naid: continuum\nurl: https://gocontinuum.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are using the Site on behalf of a company or organization, that organization\nrestricted_uses:\n- summary: Unlawful, fraudulent or harmful use\n  text: Any unlawful, fraudulent, harmful, or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/continuum/eligibility/continuum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Continuum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Returns
- Warranty
- Reverse Logistics
- Supply Chain
- Post-Sales
- Distribution
- Manufacturing
- ERP Integration
- Artificial Intelligence
---
