---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Website, products and services are intended only for personal, non-commercial use by U.S. residents over the age of 18.
  entity_types:
  - text: Our Website, products and services are intended only for personal, non-commercial use by U.S. residents over the age of 18.
    type: individual
  minimum_age:
    text: over the age of 18
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Our Website, products and services are intended only for personal, non-commercial use by U.S. residents over the age of 18.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your eligibility for products and services is subject to Splitero’s final determination, restrictions, and acceptance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Splitero
provenance_date: '2026-11-10'
provider_name: Splitero
provider_slug: splitero
slug: splitero-eligibility
source_date: '2026-11-10'
source_filename: splitero-eligibility.yml
source_heading: Eligibility
source_page: https://www.splitero.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splitero\naid: splitero\nurl: https://www.splitero.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Website, products and services are intended only for personal, non-commercial use by U.S. residents\n    over the age of 18.\nentity_types:\n- type: individual\n  text: Our Website, products and services are intended only for personal, non-commercial use by U.S. residents\n    over the age of 18.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Our Website, products and services are intended only for personal, non-commercial use by U.S.\
  \ residents\n    over the age of 18.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your eligibility for products and services is subject to Splitero’s final determination, restrictions, and\n    acceptance.\nminimum_age:\n  value: '18'\n  text: over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/splitero/eligibility/splitero-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Splitero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Real Estate
- Home Equity
- Lending
- Mortgage
- Consumer Finance
---
