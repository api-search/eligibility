---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MUST BE A PARENT, LEGAL GUARDIAN, OR OTHER ADULT TO USE OUR SERVICES
    type: individual
  minimum_age:
    text: the Services are not designed for anyone under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Use in violation of law
    text: Use the Services, intentionally or unintentionally, in connection with any violation of any applicable law or regulation
  - summary: Multiple or false accounts
    text: Have more than one account at any given time, or create an account using a false identity or information, or on behalf of someone other than yourself;
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
name: Beginlearning
provenance_date: '2026-11-09'
provider_name: Beginlearning
provider_slug: beginlearning
slug: beginlearning-eligibility
source_date: '2026-11-09'
source_filename: beginlearning-eligibility.yml
source_heading: Eligibility
source_page: https://www.beginlearning.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beginlearning\naid: beginlearning\nurl: https://www.beginlearning.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MUST BE A PARENT, LEGAL GUARDIAN, OR OTHER ADULT TO USE OUR SERVICES\nrestricted_uses:\n- summary: Use in violation of law\n  text: Use the Services, intentionally or unintentionally, in connection with any violation of any applicable law\n    or regulation\n- summary: Multiple or false accounts\n  text: Have more than one account at any given time, or create an account using a false\
  \ identity or information,\n    or on behalf of someone other than yourself;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Services are not designed for anyone under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/beginlearning/eligibility/beginlearning-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beginlearning's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Children
- Learning
- DigitalApps
- Toys
---
