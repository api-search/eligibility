---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Dashboard and Services are intended for use primarily by individuals located in the United States and may not be available in all jurisdictions.
  entity_types:
  - text: The Dashboard and Services are intended only for individuals who have reached the legal age of majority in the jurisdiction where they are located (typically 18 years or older).
    type: individual
  minimum_age:
    text: The Dashboard and Services are intended only for individuals who have reached the legal age of majority in the jurisdiction where they are located (typically 18 years or older).
    value: '18'
  restricted_uses:
  - summary: Unlawful or harassing use
    text: Use the Dashboard, Services, or any account for unlawful purposes or to transmit anything that is unlawful, libelous, harassing, or otherwise violates another person’s rights;
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
name: Zoe Financial
provenance_date: '2026-11-10'
provider_name: Zoe Financial
provider_slug: zoe-financial
slug: zoe-financial-eligibility
source_date: '2026-11-10'
source_filename: zoe-financial-eligibility.yml
source_heading: Eligibility
source_page: https://zoefinancial.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoe Financial\naid: zoe-financial\nurl: https://zoefinancial.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Dashboard and Services are intended for use primarily by individuals located in the United States and\n    may not be available in all jurisdictions.\nentity_types:\n- type: individual\n  text: The Dashboard and Services are intended only for individuals who have reached the legal age of majority\n    in the jurisdiction where they are located (typically 18 years or older).\nrestricted_uses:\n- summary: Unlawful or harassing use\n\
  \  text: Use the Dashboard, Services, or any account for unlawful purposes or to transmit anything that is unlawful,\n    libelous, harassing, or otherwise violates another person’s rights;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Dashboard and Services are intended only for individuals who have reached the legal age of majority\n    in the jurisdiction where they are located (typically 18 years or older).\n"
source_yaml_url: https://artifacts.apis.io/zoe-financial/eligibility/zoe-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zoe Financial's own page on 2026-11-10.
synthetic: false
tags:
- Wealth Management
- Financial Advisors
- TAMP
- Investment Management
- Registered Investment Adviser
- Brokerage
- Financial Services
- Portfolio Management
- Fintech
---
