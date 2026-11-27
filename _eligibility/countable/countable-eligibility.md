---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is operated from the United States and intended primarily for U.S. users.
  entity_types:
  - text: End User (“User”) Individual who accesses a Partner experience or interacts directly with Actionable to submit actions or information.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Use the Platform only for lawful purposes
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
name: Countable
provenance_date: '2026-11-09'
provider_name: Countable
provider_slug: countable
slug: countable-eligibility
source_date: '2026-11-09'
source_filename: countable-eligibility.yml
source_heading: Eligibility
source_page: https://www.myactionable.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Countable\naid: countable\nurl: https://www.myactionable.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is operated from the United States and intended primarily for U.S. users.\nentity_types:\n- type: individual\n  text: End User (“User”) Individual who accesses a Partner experience or interacts directly with Actionable to\n    submit actions or information.\nrestricted_uses:\n- summary: Lawful use only\n  text: Use the Platform only for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/countable/eligibility/countable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Countable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Civic Technology
- Government
- Advocacy
- Political Engagement
- Non-Profit
- Software-as-a-Service
---
