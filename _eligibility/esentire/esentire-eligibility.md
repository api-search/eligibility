---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  minimum_age:
    text: you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You may not use our Services for any illegal or unauthorized purpose
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
name: eSentire
provenance_date: '2026-11-09'
provider_name: eSentire
provider_slug: esentire
slug: esentire-eligibility
source_date: '2026-11-09'
source_filename: esentire-eligibility.yml
source_heading: Eligibility
source_page: https://www.esentire.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eSentire\naid: esentire\nurl: https://www.esentire.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: You may not use our Services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are at least the age\
  \ of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/esentire/eligibility/esentire-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from eSentire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Managed Detection and Response
- Threat Intelligence
- Incident Response
- MCP
- Agents
- Authentication
- Software-as-a-Service
---
