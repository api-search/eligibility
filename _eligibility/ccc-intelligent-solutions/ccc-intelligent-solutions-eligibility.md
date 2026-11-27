---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are only for use by residents of the United States, aged 18 or older and of the age of majority in their jurisdiction of residence.
  entity_types:
  - source: https://www.cccis.com/policy/terms-and-conditions
    text: I hereby irrevocably grant to CCC Intelligent Solutions Inc.
    type: individual
  minimum_age:
    text: aged 18 or older and of the age of majority in their jurisdiction of residence
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You will only use the Services for your own personal, non-commercial purposes and in accordance with these Terms. Use for any other purpose is strictly prohibited.
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
name: CCC Intelligent Solutions
provenance_date: '2026-11-09'
provider_name: CCC Intelligent Solutions
provider_slug: ccc-intelligent-solutions
slug: ccc-intelligent-solutions-eligibility
source_date: '2026-11-09'
source_filename: ccc-intelligent-solutions-eligibility.yml
source_heading: Eligibility
source_page: https://www.cccis.com/policy/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CCC Intelligent Solutions\naid: ccc-intelligent-solutions\nurl: https://www.cccis.com/policy/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.cccis.com/policy/terms-and-conditions\n  - https://www.cccis.com/policy/terms-of-use\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are only for use by residents of the United States, aged 18 or older and of the age of majority\n    in their jurisdiction of residence.\nentity_types:\n- type: individual\n  text: I hereby irrevocably grant to CCC Intelligent Solutions Inc.\n  source: https://www.cccis.com/policy/terms-and-conditions\n\
  restricted_uses:\n- summary: Non-commercial personal use only\n  text: You will only use the Services for your own personal, non-commercial purposes and in accordance with these\n    Terms. Use for any other purpose is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: aged 18 or older and of the age of majority in their jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/ccc-intelligent-solutions/eligibility/ccc-intelligent-solutions-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CCC Intelligent Solutions's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United States
- Property and Casualty
- Claims
- Auto Physical Damage
- Collision Repair
- Insurtech
- Claims Technology
- CIECA
- OAuth
- Authentication
---
