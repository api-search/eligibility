---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Promotional Credits are available only to approved Individual Investor accounts of natural persons who are legal residents of the United States; investors residing outside the United States are not eligible for Promotional Credits.
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years of age.
    type: individual
  - text: Users who have or represent a business or commercial-related enterprise that wish to invest in the Percent Entities’ offerings may elect to create a profile for themselves or for an entity they create for investment purposes.
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Securities purchases limited to accredited investors
    text: The securities offered on this Service may only be purchased by Accredited Investors, as defined by Rule 501 of Regulation D under the Securities Act of 1933, as amended.
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
name: Percent
provenance_date: '2026-11-10'
provider_name: Percent
provider_slug: percent
slug: percent-eligibility
source_date: '2026-11-10'
source_filename: percent-eligibility.yml
source_heading: Eligibility
source_page: https://percent.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Percent\naid: percent\nurl: https://percent.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Promotional Credits are available only to approved Individual Investor accounts of natural persons who are\n    legal residents of the United States; investors residing outside the United States are not eligible for Promotional\n    Credits.\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years of age.\n- type: business\n  text: Users who have or represent a business or commercial-related\
  \ enterprise that wish to invest in the Percent\n    Entities’ offerings may elect to create a profile for themselves or for an entity they create for investment\n    purposes.\nrestricted_uses:\n- summary: Securities purchases limited to accredited investors\n  text: The securities offered on this Service may only be purchased by Accredited Investors, as defined by Rule\n    501 of Regulation D under the Securities Act of 1933, as amended.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/percent/eligibility/percent-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Percent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Private Credit
- Investing
- Debt Capital Markets
- Broker-Dealer
- Asset-Backed Securities
- Financial Services
---
