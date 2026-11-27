---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Investors cannot be persons from the United States as defined in the 1933 Regulation S of the U.S. Securities Act, the U.S. Commodity Exchange Act, and 1986 In the Internal Revenue Code, as amended, as defined in FATCA or the relevant intergovernmental agreement with the United States (IGA) together with the 2015 July 24 FATCA.
  entity_types:
  - text: Both natural and legal persons can be Investors.
    type: individual
  - text: Only legal entities and individual entrepreneurs can be Borrowers.
    type: business
  minimum_age:
    text: The user (natural person) must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Loans only against real estate collateral
    text: Loans are granted only upon submission of real estate or real estate rights as collateral.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Estateguru
provenance_date: '2026-11-09'
provider_name: Estateguru
provider_slug: estateguru
slug: estateguru-eligibility
source_date: '2026-11-09'
source_filename: estateguru-eligibility.yml
source_heading: Eligibility
source_page: https://estateguru.co/user-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Estateguru\naid: estateguru\nurl: https://estateguru.co/user-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Investors cannot be persons from the United States as defined in the 1933 Regulation S of the U.S. Securities\n    Act, the U.S. Commodity Exchange Act, and 1986 In the Internal Revenue Code, as amended, as defined in FATCA\n    or the relevant intergovernmental agreement with the United States (IGA) together with the 2015 July 24 FATCA.\nentity_types:\n- type: individual\n  text: Both natural and legal persons can be Investors.\n- type: business\n\
  \  text: Only legal entities and individual entrepreneurs can be Borrowers.\nrestricted_uses:\n- summary: Loans only against real estate collateral\n  text: Loans are granted only upon submission of real estate or real estate rights as collateral.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The user (natural person) must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/estateguru/eligibility/estateguru-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Estateguru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Crowdfunding
- P2P Lending
- Fintech
- Investing
- Property Finance
- Europe
---
