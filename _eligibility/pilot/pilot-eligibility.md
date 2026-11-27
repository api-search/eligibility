---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is intended solely for business use and is intended to be viewed and used by commercial and other entities in the United States.
  entity_types:
  - text: The Site is not for individual, family, or household use
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of legal majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: No personal, family or household use
    text: You further represent and warrant that you are accessing and using the Site solely for business, commercial, or professional purposes and not for personal, family, or household use.
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
name: Pilot
provenance_date: '2026-11-10'
provider_name: Pilot
provider_slug: pilot
slug: pilot-eligibility
source_date: '2026-11-10'
source_filename: pilot-eligibility.yml
source_heading: Eligibility
source_page: https://pilot.com/terms/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pilot\naid: pilot\nurl: https://pilot.com/terms/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is intended solely for business use and is intended to be viewed and used by commercial and other\n    entities in the United States.\nentity_types:\n- type: individual\n  text: The Site is not for individual, family, or household use\nrestricted_uses:\n- summary: No personal, family or household use\n  text: You further represent and warrant that you are accessing and using the Site solely for business, commercial,\n    or professional purposes and not for\
  \ personal, family, or household use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of legal majority in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/pilot/eligibility/pilot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pilot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Bookkeeping
- Tax
- CFO Services
- Startups
- Finance
---
