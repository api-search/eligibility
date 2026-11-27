---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Minors
    text: If you are not at least eighteen (18) years old, you are prohibited from both the access and usage of Service.
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
name: Savvy
provenance_date: '2026-11-10'
provider_name: Savvy
provider_slug: savvy
slug: savvy-eligibility
source_date: '2026-11-10'
source_filename: savvy-eligibility.yml
source_heading: Eligibility
source_page: https://www.savvywealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Savvy\naid: savvy\nurl: https://www.savvywealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\nrestricted_uses:\n- summary: Minors\n  text: If you are not at least eighteen (18) years old, you are prohibited from both the access and usage of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals\
  \ at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/savvy/eligibility/savvy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Savvy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wealth Management
- Financial Services
- Investment Management
- Financial Advisors
- Financial Planning
- Fintech
- Registered Investment Advisor
---
