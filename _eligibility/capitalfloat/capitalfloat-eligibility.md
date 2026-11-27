---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: I confirm that I am a resident of India and at least 18 (Eighteen) years of age.
  entity_types:
  - text: I confirm that I am a resident of India and at least 18 (Eighteen) years of age.
    type: individual
  minimum_age:
    text: I understand that the minimum age criteria to avail personal loan facility is 23 years and maximum age criteria is 58 years.
    value: '23'
  restricted_uses:
  - summary: No capital market, gold, speculative or antisocial use
    text: will not use the Loan for any capital market use, purchase of gold/gold bullions/gold coins/gold jewellery/gold exchange traded funds/gold mutual funds or any speculative, antisocial or prohibited purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: axio and its co-lender may conduct KYC in any manner permitted under applicable law
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Capitalfloat
provenance_date: '2026-11-09'
provider_name: Capitalfloat
provider_slug: capitalfloat
slug: capitalfloat-eligibility
source_date: '2026-11-09'
source_filename: capitalfloat-eligibility.yml
source_heading: Eligibility
source_page: https://www.axio.co.in/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capitalfloat\naid: capitalfloat\nurl: https://www.axio.co.in/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: I confirm that I am a resident of India and at least 18 (Eighteen) years of age.\nentity_types:\n- type: individual\n  text: I confirm that I am a resident of India and at least 18 (Eighteen) years of age.\nrestricted_uses:\n- summary: No capital market, gold, speculative or antisocial use\n  text: will not use the Loan for any capital market use, purchase of gold/gold bullions/gold coins/gold jewellery/gold\n    exchange traded funds/gold\
  \ mutual funds or any speculative, antisocial or prohibited purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: axio and its co-lender may conduct KYC in any manner permitted under applicable law\nminimum_age:\n  value: '23'\n  text: I understand that the minimum age criteria to avail personal loan facility is 23 years and maximum age criteria\n    is 58 years.\n"
source_yaml_url: https://artifacts.apis.io/capitalfloat/eligibility/capitalfloat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Capitalfloat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Fintech
- Consumer Finance
- India
- Payments
---
