---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The website and the Services are hosted in the United States and directed to residents of the United States only. First Citizens Bank provides banking services in Arizona, California, Colorado, Florida, Georgia, Kansas, Maryland, Missouri, Nebraska, Nevada, New Mexico, North Carolina, Oklahoma, Oregon, South Carolina, Tennessee, Texas, Virginia, Washington, West Virginia and Wisconsin.
  entity_types:
  - text: The website and the Services are intended for individuals who are at least 16 years old.
    type: individual
  - text: non-commercial use of this website for your own personal or business purposes only
    type: business
  minimum_age:
    text: The website and the Services are intended for individuals who are at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: no commercial use
    text: Your unauthorized use of this website, Services or our trademarks, copyrights, or other proprietary rights, including any commercial use, automatically terminates your right to access and use this website and/or Services
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
name: First Citizens BancShares
provenance_date: '2026-11-09'
provider_name: First Citizens BancShares
provider_slug: first-citizens-bancshares
slug: first-citizens-bancshares-eligibility
source_date: '2026-11-09'
source_filename: first-citizens-bancshares-eligibility.yml
source_heading: Eligibility
source_page: https://www.firstcitizens.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: First Citizens BancShares\naid: first-citizens-bancshares\nurl: https://www.firstcitizens.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The website and the Services are hosted in the United States and directed to residents of the United States\n    only. First Citizens Bank provides banking services in Arizona, California, Colorado, Florida, Georgia, Kansas,\n    Maryland, Missouri, Nebraska, Nevada, New Mexico, North Carolina, Oklahoma, Oregon, South Carolina, Tennessee,\n    Texas, Virginia, Washington, West Virginia and Wisconsin.\nentity_types:\n- type:\
  \ individual\n  text: The website and the Services are intended for individuals who are at least 16 years old.\n- type: business\n  text: non-commercial use of this website for your own personal or business purposes only\nrestricted_uses:\n- summary: no commercial use\n  text: Your unauthorized use of this website, Services or our trademarks, copyrights, or other proprietary rights,\n    including any commercial use, automatically terminates your right to access and use this website and/or Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The website and the Services are intended for individuals who are at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/first-citizens-bancshares/eligibility/first-citizens-bancshares-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from First Citizens BancShares's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Financial Services
- Commercial Banking
- Payments
- ACH
- Wire Transfers
- Virtual Cards
- Open Banking
- Trust
- Investment
- Insurance
- United States
- Super Regional
---
