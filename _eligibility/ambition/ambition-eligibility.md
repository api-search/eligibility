---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: While the Platform is primarily designed for users in the United States, we welcome users from other regions, provided they comply with applicable local laws.
  entity_types:
  - text: The Platform is available to individuals who are 13 years of age or older.
    type: individual
  minimum_age:
    text: The Platform is available to individuals who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Sanctioned countries/parties
    text: 'you represent and warrant that you are not: (i) located in a country subject to a U.S. Government embargo'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Promotional codes can only be redeemed by verified high school students. Verification requirements may include proof of enrollment or other criteria determined by the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ambition
provenance_date: '2026-11-09'
provider_name: Ambition
provider_slug: ambition
slug: ambition-eligibility
source_date: '2026-11-09'
source_filename: ambition-eligibility.yml
source_heading: Eligibility
source_page: https://theambitionapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambition\naid: ambition\nurl: https://theambitionapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: While the Platform is primarily designed for users in the United States, we welcome users from other regions,\n    provided they comply with applicable local laws.\nentity_types:\n- type: individual\n  text: The Platform is available to individuals who are 13 years of age or older.\nrestricted_uses:\n- summary: Sanctioned countries/parties\n  text: 'you represent and warrant that you are not: (i) located in a country subject to a U.S. Government embargo'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Promotional codes can only be redeemed by verified high school students. Verification requirements may include\n    proof of enrollment or other criteria determined by the Platform.\nminimum_age:\n  value: '13'\n  text: The Platform is available to individuals who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/ambition/eligibility/ambition-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ambition's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Career Development
- Life Skills
- Mobile App
- Teens
- Consumer
---
