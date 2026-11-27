---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 16 years old
    type: individual
  - text: on behalf of your company
    type: business
  minimum_age:
    text: you are at least 16 years old
    value: '16'
  restricted_uses:
  - summary: Commercial purposes
    text: You must not use any part of the Content on our Website for commercial purposes.
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
name: Beamery
provenance_date: '2026-11-09'
provider_name: Beamery
provider_slug: beamery
slug: beamery-eligibility
source_date: '2026-11-09'
source_filename: beamery-eligibility.yml
source_heading: Eligibility
source_page: https://beamery.com/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beamery\naid: beamery\nurl: https://beamery.com/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 16 years old\n- type: business\n  text: on behalf of your company\nrestricted_uses:\n- summary: Commercial purposes\n  text: You must not use any part of the Content on our Website for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/beamery/eligibility/beamery-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beamery's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Talent
- Recruiting
- Talent CRM
- Workforce Planning
- Skills Intelligence
- Artificial Intelligence
- Software-as-a-Service
---
