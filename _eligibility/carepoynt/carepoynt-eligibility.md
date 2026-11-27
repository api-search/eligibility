---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual must be at least 18 years of age to use the Service.
    type: individual
  minimum_age:
    text: An individual must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal conduct
    text: You shall not use the Service to engage in any illegal conduct including the purchase or sale of illegal substances;
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
name: Carepoynt
provenance_date: '2026-11-09'
provider_name: Carepoynt
provider_slug: carepoynt
slug: carepoynt-eligibility
source_date: '2026-11-09'
source_filename: carepoynt-eligibility.yml
source_heading: Eligibility
source_page: https://www.carepoynt.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carepoynt\naid: carepoynt\nurl: https://www.carepoynt.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An individual must be at least 18 years of age to use the Service.\nrestricted_uses:\n- summary: Illegal conduct\n  text: You shall not use the Service to engage in any illegal conduct including the purchase or sale of illegal\n    substances;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: An individual must be at least 18 years of age to\
  \ use the Service.\n"
source_yaml_url: https://artifacts.apis.io/carepoynt/eligibility/carepoynt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Carepoynt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Rewards
- Wellness
- Platform
---
