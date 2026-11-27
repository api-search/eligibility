---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service.
    type: individual
  - text: In the event a company uses the Services, such use shall be limited to the company’s internal use.
    type: business
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited content and use
    text: The following are examples of the kind of content and/or use that is illegal or prohibited by Harness.
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
name: Harness Wealth
provenance_date: '2026-11-09'
provider_name: Harness Wealth
provider_slug: harness-wealth
slug: harness-wealth-eligibility
source_date: '2026-11-09'
source_filename: harness-wealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.harness.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harness Wealth\naid: harness-wealth\nurl: https://www.harness.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service.\n- type: business\n  text: In the event a company uses the Services, such use shall be limited to the company’s internal use.\nrestricted_uses:\n- summary: Illegal or prohibited content and use\n  text: The following are examples of the kind of content and/or use that is illegal or prohibited by Harness.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/harness-wealth/eligibility/harness-wealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Harness Wealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Tax
- Wealth Management
- Accounting
- Investment Advisory
- Marketplace
- Professional Services
- Fintech
---
