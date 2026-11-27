---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: each natural, legal or any other entity or association (hereinafter referred to as the user) who visits or uses the chemius.net website
    type: other
  minimum_age:
    text: null
    value: null
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
name: Chemius
provenance_date: '2026-11-09'
provider_name: Chemius
provider_slug: chemius
slug: chemius-eligibility
source_date: '2026-11-09'
source_filename: chemius-eligibility.yml
source_heading: Eligibility
source_page: https://www.chemius.net/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chemius\naid: chemius\nurl: https://www.chemius.net/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: each natural, legal or any other entity or association (hereinafter referred to as the user) who visits\n    or uses the chemius.net website\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chemius/eligibility/chemius-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Chemius's own page on 2026-11-09.
synthetic: false
tags:
- ADR
- Artificial Intelligence
- Chemicals
- Chemists
- Compliance
- GHS
- Hazard Communication
- Labels
- Reach
- Regulatory
- Research
- Safety Data Sheets
- Software-as-a-Service
- TDS
---
