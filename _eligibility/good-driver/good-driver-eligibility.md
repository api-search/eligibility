---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Interface is only available to users in certain jurisdictions who can use the Interface as permitted under applicable laws.
  entity_types:
  - text: You may use the Interface only if you are at least 18 years old, capable of forming a binding contract with Good Driver, have a valid, unrevoked, unsuspended driver license
    type: individual
  minimum_age:
    text: You may use the Interface only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: Use the Interface, or any portion thereof, for any commercial purpose or for the benefit of any third party or in any manner not permitted by these Terms
  - summary: No sanctioned-country or restricted-party use
    text: you are not located in a country that is subject to a U.S. Government embargo; and (b) you are not listed on any U.S. Government list of prohibited, sanctioned, or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For certain features of the Interface, including creating and modifying a Plan, as defined below, you will need a user account. This user account will require you to connect a bank account to the Interface.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Good Driver
provenance_date: '2026-11-09'
provider_name: Good Driver
provider_slug: good-driver
slug: good-driver-eligibility
source_date: '2026-11-09'
source_filename: good-driver-eligibility.yml
source_heading: Eligibility
source_page: https://www.gooddriver.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Good Driver\naid: good-driver\nurl: https://www.gooddriver.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Interface is only available to users in certain jurisdictions who can use the Interface as permitted\n    under applicable laws.\nentity_types:\n- type: individual\n  text: You may use the Interface only if you are at least 18 years old, capable of forming a binding contract with\n    Good Driver, have a valid, unrevoked, unsuspended driver license\nrestricted_uses:\n- summary: No commercial use\n  text: Use the Interface, or any portion thereof,\
  \ for any commercial purpose or for the benefit of any third party\n    or in any manner not permitted by these Terms\n- summary: No sanctioned-country or restricted-party use\n  text: you are not located in a country that is subject to a U.S. Government embargo; and (b) you are not listed\n    on any U.S. Government list of prohibited, sanctioned, or restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For certain features of the Interface, including creating and modifying a Plan, as defined below, you will\n    need a user account. This user account will require you to connect a bank account to the Interface.\nminimum_age:\n  value: '18'\n  text: You may use the Interface only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/good-driver/eligibility/good-driver-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Good Driver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Auto Insurance
- Financial Services
- Mobile App
- Consumer
- Vehicle Coverage
---
