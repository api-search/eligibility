---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of BlissClub is available only to individuals who are (i) at least 18 years old and can form legally binding contracts under applicable law, or in the alternative (ii) under 18 years of age, but their legal guardians have agreed to enter into contract on their behalf
    type: individual
  - text: If you use BlissClub or open an Account (as defined below) on behalf of a non-individual entity or group, you represent and warrant that you have the authority to bind that entity or group
    type: business
  minimum_age:
    text: at least 18 years old and can form legally binding contracts under applicable law
    value: '18'
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
name: Blissclub
provenance_date: '2026-11-09'
provider_name: Blissclub
provider_slug: blissclub
slug: blissclub-eligibility
source_date: '2026-11-09'
source_filename: blissclub-eligibility.yml
source_heading: Eligibility
source_page: https://blissclub.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blissclub\naid: blissclub\nurl: https://blissclub.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of BlissClub is available only to individuals who are (i) at least 18 years old and can form legally\n    binding contracts under applicable law, or in the alternative (ii) under 18 years of age, but their legal guardians\n    have agreed to enter into contract on their behalf\n- type: business\n  text: If you use BlissClub or open an Account (as defined below) on behalf of a non-individual entity or group,\n\
  \    you represent and warrant that you have the authority to bind that entity or group\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old and can form legally binding contracts under applicable law\n"
source_yaml_url: https://artifacts.apis.io/blissclub/eligibility/blissclub-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Blissclub's own page on 2026-11-09.
synthetic: false
tags:
- Apparel
- E-Commerce
- Fashion
- Activewear
- Indian
---
