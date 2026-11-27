---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BrandPresence is designed primarily for business and professional use.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No deceptive claims or harassment
    text: Do not use findings to make deceptive claims, harass competitors, or violate third-party terms.
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
name: BrandPresence
provenance_date: '2026-11-09'
provider_name: BrandPresence
provider_slug: brandpresence-dev
slug: brandpresence-dev-eligibility
source_date: '2026-11-09'
source_filename: brandpresence-dev-eligibility.yml
source_heading: Eligibility
source_page: https://brandpresence.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrandPresence\naid: brandpresence-dev\nurl: https://brandpresence.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: BrandPresence is designed primarily for business and professional use.\nrestricted_uses:\n- summary: No deceptive claims or harassment\n  text: Do not use findings to make deceptive claims, harass competitors, or violate third-party terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brandpresence-dev/eligibility/brandpresence-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from BrandPresence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Monitoring
- Search
- Visibility
---
