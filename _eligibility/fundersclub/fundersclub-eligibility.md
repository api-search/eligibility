---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some products and services described in the Site may not be available in all jurisdictions or to all clients.
  entity_types:
  - text: The Service is available only to Accredited Investors who are at least 18 years old. You represent and warrant that if you are an individual, you are of legal age to form a binding contract
    type: individual
  - text: If you are using the Site on behalf of any entity, you represent and warrant that you are authorized to accept this Agreement on such entity's behalf
    type: business
  minimum_age:
    text: The Service is available only to Accredited Investors who are at least 18 years old.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Such authorization may require completion of an accredited investor questionnaire and satisfactory background information screening and/or identification verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FundersClub
provenance_date: '2026-11-09'
provider_name: FundersClub
provider_slug: fundersclub
slug: fundersclub-eligibility
source_date: '2026-11-09'
source_filename: fundersclub-eligibility.yml
source_heading: Eligibility
source_page: https://fundersclub.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FundersClub\naid: fundersclub\nurl: https://fundersclub.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some products and services described in the Site may not be available in all jurisdictions or to all clients.\nentity_types:\n- type: individual\n  text: The Service is available only to Accredited Investors who are at least 18 years old. You represent and warrant\n    that if you are an individual, you are of legal age to form a binding contract\n- type: business\n  text: If you are using the Site on behalf of any entity, you represent and warrant that you are\
  \ authorized to\n    accept this Agreement on such entity's behalf\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Such authorization may require completion of an accredited investor questionnaire and satisfactory background\n    information screening and/or identification verification.\nminimum_age:\n  value: '18'\n  text: The Service is available only to Accredited Investors who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/fundersclub/eligibility/fundersclub-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from FundersClub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Venture Capital
- Startups
- Investing
- Fintech
- Private Markets
- Fund Administration
---
