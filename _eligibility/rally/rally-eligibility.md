---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Rally operates the Service from its headquarters in the United States, and the Service is intended only for users within the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investments limited to qualified purchasers
    text: is subject to the qualification of the User as a qualified purchaser (as determined by the applicable securities laws of the United States, as amended from time to time) and further application, as determined by Rally in its sole discretion.
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
name: Rally
provenance_date: '2026-11-10'
provider_name: Rally
provider_slug: rally
slug: rally-eligibility
source_date: '2026-11-10'
source_filename: rally-eligibility.yml
source_heading: Eligibility
source_page: https://rallyrd.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rally\naid: rally\nurl: https://rallyrd.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Rally operates the Service from its headquarters in the United States, and the Service is intended only\n    for users within the United States.\nentity_types: []\nrestricted_uses:\n- summary: Investments limited to qualified purchasers\n  text: is subject to the qualification of the User as a qualified purchaser (as determined by the applicable securities\n    laws of the United States, as amended from time to time) and further application, as determined by Rally in\n    its\
  \ sole discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rally/eligibility/rally-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Rally's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Alternative Assets
- Investing
- Collectibles
- Fractional Ownership
- Fintech
- Marketplace
---
