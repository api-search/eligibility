---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside outside of the United States, this provision applies to any action you bring against Doma in the United States.
  entity_types:
  - text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the Site
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to enter into legally binding contracts
    value: '18'
  restricted_uses:
  - summary: Only the stated Purpose
    text: use the Site for any purpose other than the Purpose
  - summary: No commercial use beyond permitted
    text: use the Site or Collective Content for any commercial or other purposes that are not expressly permitted by these Terms
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
name: Doma
provenance_date: '2026-11-09'
provider_name: Doma
provider_slug: doma
slug: doma-eligibility
source_date: '2026-11-09'
source_filename: doma-eligibility.yml
source_heading: Eligibility
source_page: https://doma.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doma\naid: doma\nurl: https://doma.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you reside outside of the United States, this provision applies to any action you bring against Doma\n    in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the\n    Site\nrestricted_uses:\n- summary: Only the stated Purpose\n  text: use the Site for any purpose other than the Purpose\n- summary: No commercial use beyond permitted\n  text: use the Site or Collective\
  \ Content for any commercial or other purposes that are not expressly permitted\n    by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into legally binding contracts\n"
source_yaml_url: https://artifacts.apis.io/doma/eligibility/doma-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Doma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Title Insurance
- Mortgage
- Real Estate Technology
- PropTech
- Fintech
- Closing
- Artificial Intelligence
---
