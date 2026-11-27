---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, " Company "), you represent and warrant that you have the authority to bind the Company to this Agreement.
    type: business
  minimum_age:
    text: The Site is only intended for individuals aged fourteen (14) years or older.
    value: '14'
  restricted_uses:
  - summary: Competitive purposes
    text: use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the activities, services, or products offered by Air Security
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
name: AIR
provenance_date: '2026-11-09'
provider_name: AIR
provider_slug: air
slug: air-eligibility
source_date: '2026-11-09'
source_filename: air-eligibility.yml
source_heading: Eligibility
source_page: https://www.air.security/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIR\naid: air\nurl: https://www.air.security/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, \" Company\n    \"), you represent and warrant that you have the authority to bind the Company to this Agreement.\nrestricted_uses:\n- summary: Competitive purposes\n  text: use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the activities,\n    services, or products offered by Air Security\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: The Site is only intended for individuals aged fourteen (14) years or older.\n"
source_yaml_url: https://artifacts.apis.io/air/eligibility/air-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AIR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Cloud
- Artificial Intelligence
- Security
---
