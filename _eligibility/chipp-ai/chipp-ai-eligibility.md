---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a national of, a country or territory subject to comprehensive U.S. embargoes, or if you are on any U.S. government denied-party list.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and able to form a binding contract to use the Services.
    type: individual
  - text: “Customer,” “you,” or “your” refers to the individual or entity that creates an account on the Services or builds or operates Creator Apps
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Regulated and sensitive data
    text: Customer may not submit to the Services, or collect through a Creator App, health information (including information protected by HIPAA), children’s data, financial data, biometric data, or any other regulated or sensitive data unless (a) the applicable Plan or Order and Customer’s configuration of the Services support that use
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
name: chipp-ai
provenance_date: '2026-11-09'
provider_name: chipp-ai
provider_slug: chipp-ai
slug: chipp-ai-eligibility
source_date: '2026-11-09'
source_filename: chipp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://chipp.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chipp-ai\naid: chipp-ai\nurl: https://chipp.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a national of, a country or territory subject to\n    comprehensive U.S. embargoes, or if you are on any U.S. government denied-party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and able to form a binding\n    contract to use the Services.\n- type: business\n  text: “Customer,” “you,” or “your” refers to the individual or entity that creates\
  \ an account on the Services\n    or builds or operates Creator Apps\nrestricted_uses:\n- summary: Regulated and sensitive data\n  text: Customer may not submit to the Services, or collect through a Creator App, health information (including\n    information protected by HIPAA), children’s data, financial data, biometric data, or any other regulated or\n    sensitive data unless (a) the applicable Plan or Order and Customer’s configuration of the Services support\n    that use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/chipp-ai/eligibility/chipp-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from chipp-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Software-as-a-Service
- HIPAA
- SOC 2
---
