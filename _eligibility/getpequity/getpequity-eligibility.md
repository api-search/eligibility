---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will only use the Pequity Platform in jurisdictions where the Pequity Platform may lawfully be used.
  entity_types:
  - text: tools and resources that may be helpful in managing, supporting, or improving compensation, recruitment, and human resources processes for corporate entities
    type: business
  - text: you have reached the age of majority in your jurisdiction of residence
    type: individual
  minimum_age:
    text: you have reached the age of majority in your jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Purposes other than Permitted Use
    text: You will not, without our prior written permission, use the Pequity Platform for purposes other than the Permitted Use.
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
name: Pequity
provenance_date: '2026-11-09'
provider_name: Pequity
provider_slug: getpequity
slug: getpequity-eligibility
source_date: '2026-11-09'
source_filename: getpequity-eligibility.yml
source_heading: Eligibility
source_page: https://pequity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pequity\naid: getpequity\nurl: https://pequity.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will only use the Pequity Platform in jurisdictions where the Pequity Platform may lawfully be used.\nentity_types:\n- type: business\n  text: tools and resources that may be helpful in managing, supporting, or improving compensation, recruitment,\n    and human resources processes for corporate entities\n- type: individual\n  text: you have reached the age of majority in your jurisdiction of residence\nrestricted_uses:\n- summary: Purposes other than Permitted Use\n  text:\
  \ You will not, without our prior written permission, use the Pequity Platform for purposes other than the\n    Permitted Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you have reached the age of majority in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/getpequity/eligibility/getpequity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pequity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compensation
- Human Resources
- Payroll
- Software-as-a-Service
- Total Rewards
- Compensation Management
---
