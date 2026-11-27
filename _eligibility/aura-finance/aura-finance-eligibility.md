---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Usage of aurafinance.io and the Service is age restricted : to access and use aurafinance.io and its Service the User must be an adult under applicable law.'
    type: individual
  - text: Business User Any User that does not qualify as a Consumer.
    type: business
  minimum_age:
    text: the User must be an adult under applicable law.
    value: adult
  restricted_uses:
  - summary: Acceptable use limits
    text: Aurafinance.io and the Service may only be used within the scope of what they are provided for, under these Terms and applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service Users must register or create a User account, providing all required data or information in a complete and truthful manner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aura Finance
provenance_date: '2026-11-09'
provider_name: Aura Finance
provider_slug: aura-finance
slug: aura-finance-eligibility
source_date: '2026-11-09'
source_filename: aura-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.iubenda.com/terms-and-conditions/81561130
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aura Finance\naid: aura-finance\nurl: https://www.iubenda.com/terms-and-conditions/81561130\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Usage of aurafinance.io and the Service is age restricted : to access and use aurafinance.io and its Service\n    the User must be an adult under applicable law.'\n- type: business\n  text: Business User Any User that does not qualify as a Consumer.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: Aurafinance.io and the Service may only be used within the scope of what they are provided\
  \ for, under these\n    Terms and applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service Users must register or create a User account, providing all required data or information\n    in a complete and truthful manner.\nminimum_age:\n  value: adult\n  text: the User must be an adult under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/aura-finance/eligibility/aura-finance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Aura Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Financial Wellness
- Fintech
- Investing
- Employee Benefits
- Personal Finance
---
