---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: In the case of Investors, the Alto Platform is available only to United States residents.
  entity_types:
  - text: The Alto Platform is available only to persons who are at least eighteen (18) years old
    type: individual
  - text: legal entities otherwise capable of forming legally binding contracts under applicable law
    type: business
  minimum_age:
    text: The Alto Platform is available only to persons who are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Accredited investor offerings
    text: Certain of these investments may be offered by Issuers only to investors who are “accredited investors,” and you represent and warrant that any information submitted by you through the Alto Platform regarding your status as an accredited investor will be true and correct.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You agree to provide the personal information requested by Alto to comply with this program, including your name, address, date of birth, and tax identification number, and, upon request, to provide a readable copy of an unexpired, photo-bearing, government-issued identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alto
provenance_date: '2026-11-09'
provider_name: Alto
provider_slug: alto
slug: alto-eligibility
source_date: '2026-11-09'
source_filename: alto-eligibility.yml
source_heading: Eligibility
source_page: https://www.altoira.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alto\naid: alto\nurl: https://www.altoira.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: In the case of Investors, the Alto Platform is available only to United States residents.\nentity_types:\n- type: individual\n  text: The Alto Platform is available only to persons who are at least eighteen (18) years old\n- type: business\n  text: legal entities otherwise capable of forming legally binding contracts under applicable law\nrestricted_uses:\n- summary: Accredited investor offerings\n  text: Certain of these investments may be offered by Issuers only to\
  \ investors who are “accredited investors,”\n    and you represent and warrant that any information submitted by you through the Alto Platform regarding your\n    status as an accredited investor will be true and correct.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You agree to provide the personal information requested by Alto to comply with this program, including your\n    name, address, date of birth, and tax identification number, and, upon request, to provide a readable copy of\n    an unexpired, photo-bearing, government-issued identification\nminimum_age:\n  value: '18'\n  text: The Alto Platform is available only to persons who are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/alto/eligibility/alto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Alto's own page on 2026-11-09.
synthetic: false
tags:
- Private Markets
- Retirement Accounts
- IRA
- Wealth Advisors
- Issuers
- Self-Directed Investing
- Alternative Investments
---
