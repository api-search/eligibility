---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Primary Accountholder is a natural person at least eighteen (18) years of age (or older if residing in a state where the age of majority is older than eighteen (18))
    type: individual
  minimum_age:
    text: The Primary Accountholder is a natural person at least eighteen (18) years of age (or older if residing in a state where the age of majority is older than eighteen (18))
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Card enrollment requires completion of the identity verification process (KYC) as described in the Cardholder Agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Greenlight
provenance_date: '2026-11-09'
provider_name: Greenlight
provider_slug: greenlight
slug: greenlight-eligibility
source_date: '2026-11-09'
source_filename: greenlight-eligibility.yml
source_heading: Eligibility
source_page: https://greenlight.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greenlight\naid: greenlight\nurl: https://greenlight.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Primary Accountholder is a natural person at least eighteen (18) years of age (or older if residing\n    in a state where the age of majority is older than eighteen (18))\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Card enrollment requires completion of the identity verification process (KYC) as described in the Cardholder\n    Agreement.\n\
  minimum_age:\n  value: '18'\n  text: The Primary Accountholder is a natural person at least eighteen (18) years of age (or older if residing\n    in a state where the age of majority is older than eighteen (18))\n"
source_yaml_url: https://artifacts.apis.io/greenlight/eligibility/greenlight-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Greenlight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Family Finance
- Banking
- Debit Cards
- Kids Banking
- Investing
- Financial Literacy
- Payments
- Mobile App
- Education
---
