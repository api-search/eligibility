---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are using the Website for your own personal use
    type: individual
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: you are using the Website for your own personal use
  - summary: Sanctions and export compliance
    text: THOROPASS prohibits Customers from using THOROPASS’s software or services in violation of the Export Administration Regulations (EAR) or Office of Foreign Assets Control (OFAC) Sanctions.
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
name: Thoropass
provenance_date: '2026-11-10'
provider_name: Thoropass
provider_slug: thoropass
slug: thoropass-eligibility
source_date: '2026-11-10'
source_filename: thoropass-eligibility.yml
source_heading: Eligibility
source_page: https://www.thoropass.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thoropass\naid: thoropass\nurl: https://www.thoropass.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are using the Website for your own personal use\nrestricted_uses:\n- summary: Personal use only\n  text: you are using the Website for your own personal use\n- summary: Sanctions and export compliance\n  text: THOROPASS prohibits Customers from using THOROPASS’s software or services in violation of the Export Administration\n    Regulations (EAR) or Office of Foreign Assets Control (OFAC) Sanctions.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/thoropass/eligibility/thoropass-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Thoropass's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Compliance
- Compliance Automation
- Audit
- Security
- Cybersecurity
- GRC
- SOC 2
- MCP
---
