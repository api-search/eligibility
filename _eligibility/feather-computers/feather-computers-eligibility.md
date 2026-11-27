---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Country refers to California, United States.
  entity_types:
  - text: You represent that You are at least 18 years old.
    type: individual
  - text: You means the individual user, or the company, or legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: business
  minimum_age:
    text: You represent that You are at least 18 years old. The Service is not intended for individuals under 18, and such individuals are not permitted to use it.
    value: '18'
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
name: Feather Computers
provenance_date: '2026-11-09'
provider_name: Feather Computers
provider_slug: feather-computers
slug: feather-computers-eligibility
source_date: '2026-11-09'
source_filename: feather-computers-eligibility.yml
source_heading: Eligibility
source_page: https://feather.computer/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Feather Computers\naid: feather-computers\nurl: https://feather.computer/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Country refers to California, United States.\nentity_types:\n- type: individual\n  text: You represent that You are at least 18 years old.\n- type: business\n  text: You means the individual user, or the company, or legal entity on behalf of which such individual is accessing\n    or using the Service, as applicable.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: You represent that You are at least 18 years old. The Service is not intended for individuals under 18,\n    and such individuals are not permitted to use it.\n"
source_yaml_url: https://artifacts.apis.io/feather-computers/eligibility/feather-computers-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Feather Computers's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Email
- Productivity
- Software-as-a-Service
---
