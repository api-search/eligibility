---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these Terms on behalf of an organisation, you represent and warrant that you have authority to bind that organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data routing at customer's risk
    text: If Customer routes Customer Data that includes payment card data, government-issued identification numbers, health information, biometric data or other sensitive personal information, Customer does so at its own risk
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
name: Support Fusion
provenance_date: '2026-11-10'
provider_name: Support Fusion
provider_slug: suppfusion
slug: suppfusion-eligibility
source_date: '2026-11-10'
source_filename: suppfusion-eligibility.yml
source_heading: Eligibility
source_page: https://www.suppfusion.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Support Fusion\naid: suppfusion\nurl: https://www.suppfusion.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of an organisation, you represent and warrant that you have authority\n    to bind that organisation\nrestricted_uses:\n- summary: Sensitive data routing at customer's risk\n  text: If Customer routes Customer Data that includes payment card data, government-issued identification numbers,\n    health information, biometric data or other sensitive personal information, Customer does\
  \ so at its own risk\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/suppfusion/eligibility/suppfusion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Support Fusion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- IT
- Integration
- Collaboration
- Support
---
