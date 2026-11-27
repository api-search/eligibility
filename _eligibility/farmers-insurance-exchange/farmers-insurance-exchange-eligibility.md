---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Not all of the products or services described on the Sites are available in all geographic areas of the United States. We make no representation that the content of the Sites is appropriate or available for use outside the United States.
  entity_types:
  - text: The online calculators are for personal use only and are provided on an AS IS basis
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use of calculators
    text: The online calculators are for personal use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to determine all eligibility for such products or services at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Farmers Insurance Exchange
provenance_date: '2026-11-09'
provider_name: Farmers Insurance Exchange
provider_slug: farmers-insurance-exchange
slug: farmers-insurance-exchange-eligibility
source_date: '2026-11-09'
source_filename: farmers-insurance-exchange-eligibility.yml
source_heading: Eligibility
source_page: https://www.farmers.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Farmers Insurance Exchange\naid: farmers-insurance-exchange\nurl: https://www.farmers.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Not all of the products or services described on the Sites are available in all geographic areas of the\n    United States. We make no representation that the content of the Sites is appropriate or available for use outside\n    the United States.\nentity_types:\n- type: individual\n  text: The online calculators are for personal use only and are provided on an AS IS basis\nrestricted_uses:\n- summary: Personal use of calculators\n\
  \  text: The online calculators are for personal use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to determine all eligibility for such products or services at our sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/farmers-insurance-exchange/eligibility/farmers-insurance-exchange-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Farmers Insurance Exchange's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Insurance
- Property and Casualty
- Auto Insurance
- Home Insurance
- Financial Services
- United States
---
