---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services that may be accessed from, displayed on, or linked to from your device are not available in all languages or in all countries.
  entity_types:
  - text: If you are accessing the Sites in your individual capacity and there is no applicable Services Agreement with Company
    type: individual
  - text: IF YOU AGREE TO THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY (THE "ORGANIZATION")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Developing or training AI
    text: To develop, train, or improve artificial intelligence, tools, or products.
  - summary: Reliance on AI output for legal, financial, health or employment decisions
    text: You shall not rely on any output for legal, financial, health, or employment decisions
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
name: SurePayroll
provenance_date: '2026-11-10'
provider_name: SurePayroll
provider_slug: surepayroll
slug: surepayroll-eligibility
source_date: '2026-11-10'
source_filename: surepayroll-eligibility.yml
source_heading: Eligibility
source_page: https://www.surepayroll.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SurePayroll\naid: surepayroll\nurl: https://www.surepayroll.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services that may be accessed from, displayed on, or linked to from your device are not available in all\n    languages or in all countries.\nentity_types:\n- type: individual\n  text: If you are accessing the Sites in your individual capacity and there is no applicable Services Agreement\n    with Company\n- type: business\n  text: IF YOU AGREE TO THESE TERMS ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY (THE \"ORGANIZATION\")\nrestricted_uses:\n- summary:\
  \ Developing or training AI\n  text: To develop, train, or improve artificial intelligence, tools, or products.\n- summary: Reliance on AI output for legal, financial, health or employment decisions\n  text: You shall not rely on any output for legal, financial, health, or employment decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/surepayroll/eligibility/surepayroll-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from SurePayroll's own page on 2026-11-10.
synthetic: false
tags:
- Payroll
- Human Resources
- Small Business
- Paychex
- Cloud Services
---
