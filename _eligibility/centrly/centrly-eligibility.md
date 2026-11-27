---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use is not permitted by local law or regulation.
  entity_types:
  - text: If you are accessing and using the Service for your organization or entity (“entity”), then you are agreeing to the Agreement for that entity
    type: business
  minimum_age:
    text: You affirm that you are more than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited ML Tools activities
    text: 'you and/or your users shall not: perform any illegal activity; generate any hateful, harassing, or violent content; generate malware'
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
name: Centrly
provenance_date: '2026-11-09'
provider_name: Centrly
provider_slug: centrly
slug: centrly-eligibility
source_date: '2026-11-09'
source_filename: centrly-eligibility.yml
source_heading: Eligibility
source_page: https://www.centrl.ai/legal/terms-of-use-for-guests/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centrly\naid: centrly\nurl: https://www.centrl.ai/legal/terms-of-use-for-guests/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is not intended for distribution to, or use by, any person or entity in any jurisdiction or\n    country where such distribution or use is not permitted by local law or regulation.\nentity_types:\n- type: business\n  text: If you are accessing and using the Service for your organization or entity (“entity”), then you are agreeing\n    to the Agreement for that entity\nrestricted_uses:\n- summary: Prohibited ML Tools activities\n  text: 'you\
  \ and/or your users shall not: perform any illegal activity; generate any hateful, harassing, or violent\n    content; generate malware'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are more than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/centrly/eligibility/centrly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Centrly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Workflow Automation
- Software-as-a-Service
- Enterprise
---
