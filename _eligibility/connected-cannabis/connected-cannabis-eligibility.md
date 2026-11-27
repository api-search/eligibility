---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This site is intended for users located in the United States.
  entity_types:
  - text: THIS SITE IS INTENDED FOR USERS (21) TWENTY ONE YEARS OF AGE OR OLDER.
    type: individual
  minimum_age:
    text: THIS SITE IS INTENDED FOR USERS (21) TWENTY ONE YEARS OF AGE OR OLDER.
    value: '21'
  restricted_uses:
  - summary: No commercial use of Site or products
    text: This license does not allow you to resell or make any commercial use of the Site, its Contents or our products sold through the Site
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
name: Connected Cannabis
provenance_date: '2026-11-09'
provider_name: Connected Cannabis
provider_slug: connected-cannabis
slug: connected-cannabis-eligibility
source_date: '2026-11-09'
source_filename: connected-cannabis-eligibility.yml
source_heading: Eligibility
source_page: https://connectedcannabisco.com/pages/tos-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Connected Cannabis\naid: connected-cannabis\nurl: https://connectedcannabisco.com/pages/tos-privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This site is intended for users located in the United States.\nentity_types:\n- type: individual\n  text: THIS SITE IS INTENDED FOR USERS (21) TWENTY ONE YEARS OF AGE OR OLDER.\nrestricted_uses:\n- summary: No commercial use of Site or products\n  text: This license does not allow you to resell or make any commercial use of the Site, its Contents or our products\n    sold through the Site\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: THIS SITE IS INTENDED FOR USERS (21) TWENTY ONE YEARS OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/connected-cannabis/eligibility/connected-cannabis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Connected Cannabis's own page on 2026-11-09.
synthetic: false
tags:
- Cannabis
- Retail
- E-Commerce
- California
- Dispensary
---
