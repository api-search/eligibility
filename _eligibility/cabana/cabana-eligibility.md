---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We currently serve customers in California only.
  entity_types:
  - text: You must be at least 16 years old to use the Site, and at least 18 and able to enter a binding contract to buy service.
    type: individual
  - text: If you are using the Site for a business, you confirm you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Site, and at least 18 and able to enter a binding contract to buy service.
    value: '16'
  restricted_uses:
  - summary: Unlawful or false submissions
    text: Submit false information, someone else's contact details, or a request for service at an address you have no right to;
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
name: Cabana
provenance_date: '2026-11-09'
provider_name: Cabana
provider_slug: cabana
slug: cabana-eligibility
source_date: '2026-11-09'
source_filename: cabana-eligibility.yml
source_heading: Eligibility
source_page: https://cabanapools.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cabana\naid: cabana\nurl: https://cabanapools.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We currently serve customers in California only.\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Site, and at least 18 and able to enter a binding contract\n    to buy service.\n- type: business\n  text: If you are using the Site for a business, you confirm you are authorized to bind it.\nrestricted_uses:\n- summary: Unlawful or false submissions\n  text: Submit false information, someone else's contact details, or a request\
  \ for service at an address you have\n    no right to;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Site, and at least 18 and able to enter a binding contract\n    to buy service.\n"
source_yaml_url: https://artifacts.apis.io/cabana/eligibility/cabana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cabana's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pool Services
- Home Services
- Maintenance
- California
- Local Services
---
