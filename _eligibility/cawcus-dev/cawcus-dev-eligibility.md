---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old, or the minimum age of digital consent in your jurisdiction, to create an account.
    value: '16'
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
name: Cawcus
provenance_date: '2026-11-09'
provider_name: Cawcus
provider_slug: cawcus-dev
slug: cawcus-dev-eligibility
source_date: '2026-11-09'
source_filename: cawcus-dev-eligibility.yml
source_heading: Eligibility
source_page: https://cawcus.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cawcus\naid: cawcus-dev\nurl: https://cawcus.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or the minimum age of digital consent in your jurisdiction, to create\n    an account.\n"
source_yaml_url: https://artifacts.apis.io/cawcus-dev/eligibility/cawcus-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Cawcus's own page on 2026-11-09.
synthetic: false
tags:
- Feedback
- Artificial Intelligence
- Product Management
- Software-as-a-Service
- Collaboration
---
