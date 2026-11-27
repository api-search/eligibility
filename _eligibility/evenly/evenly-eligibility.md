---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Evenly.com is for Use in the United States. The Site is hosted in the United States and is intended for users located in the United States.
  entity_types:
  - text: The Site is for the personal use of individuals only and may not be used in connection with any commercial endeavors.
    type: individual
  - text: Organizations, companies and/or businesses may not use the Services, the Site Information or the Site for any purpose without written consent of or agreement with Evenly.
    type: business
  minimum_age:
    text: The Site and the Services are not intended for users under the age of 18. To register for any Services offered on the Site, you must be 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: may not be used in connection with any commercial endeavors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All referrals and subsequent bonuses are subject to review and approval by Evenly Opco, LLC
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evenly
provenance_date: '2026-11-09'
provider_name: Evenly
provider_slug: evenly
slug: evenly-eligibility
source_date: '2026-11-09'
source_filename: evenly-eligibility.yml
source_heading: Eligibility
source_page: https://www.evenly.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evenly\naid: evenly\nurl: https://www.evenly.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Evenly.com is for Use in the United States. The Site is hosted in the United States and is intended for\n    users located in the United States.\nentity_types:\n- type: individual\n  text: The Site is for the personal use of individuals only and may not be used in connection with any commercial\n    endeavors.\n- type: business\n  text: Organizations, companies and/or businesses may not use the Services, the Site Information or the Site for\n    any purpose without\
  \ written consent of or agreement with Evenly.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: may not be used in connection with any commercial endeavors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All referrals and subsequent bonuses are subject to review and approval by Evenly Opco, LLC\nminimum_age:\n  value: '18'\n  text: The Site and the Services are not intended for users under the age of 18. To register for any Services offered\n    on the Site, you must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/evenly/eligibility/evenly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Evenly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dental
- Orthodontics
- Software-as-a-Service
- Healthcare
---
