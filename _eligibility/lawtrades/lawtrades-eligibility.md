---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is administered in the U.S. and intended for U.S. users; any use outside of the U.S. is at the users own risk
  entity_types:
  - text: You must be 18 years of age or over, or the legal age to form a binding contract in your jurisdiction if that age is greater than 18 years of age
    type: individual
  - text: If you are registering an account or using the Site or Platform on behalf of an individual or entity other than yourself
    type: business
  minimum_age:
    text: You must be 18 years of age or over, or the legal age to form a binding contract in your jurisdiction if that age is greater than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: You may use the Site and the Services for lawful, non-commercial purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Lawtrades or its vendors may require proof of identity to access or use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LawTrades
provenance_date: '2026-11-09'
provider_name: LawTrades
provider_slug: lawtrades
slug: lawtrades-eligibility
source_date: '2026-11-09'
source_filename: lawtrades-eligibility.yml
source_heading: Eligibility
source_page: https://www.lawtrades.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawTrades\naid: lawtrades\nurl: https://www.lawtrades.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is administered in the U.S. and intended for U.S. users; any use outside of the U.S. is at the\n    users own risk\nentity_types:\n- type: individual\n  text: You must be 18 years of age or over, or the legal age to form a binding contract in your jurisdiction if\n    that age is greater than 18 years of age\n- type: business\n  text: If you are registering an account or using the Site or Platform on behalf of an individual or entity other\n    than yourself\n\
  restricted_uses:\n- summary: Non-commercial use only\n  text: You may use the Site and the Services for lawful, non-commercial purposes only.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Lawtrades or its vendors may require proof of identity to access or use the Service.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or over, or the legal age to form a binding contract in your jurisdiction if\n    that age is greater than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/lawtrades/eligibility/lawtrades-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from LawTrades's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Services
- Legal Operations
- Marketplace
- Talent Marketplace
- Contracts
- Compliance
- Professional Services
- Artificial Intelligence
---
