---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for users in the United States. We make no representation that the Website or its content is appropriate or available in other locations.
  entity_types:
  - text: 'By using the Website, you represent and warrant that: You are at least 18 years of age, or the age of legal majority in your jurisdiction if higher'
    type: individual
  - text: If you are using the Website on behalf of an organization, you represent and warrant that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You are at least 18 years of age, or the age of legal majority in your jurisdiction if higher
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You are not located in a country subject to a U.S. government embargo or designated as a “terrorist supporting” country; You are not listed on any U.S. government list of prohibited or restricted parties;
  - summary: Acceptable use restrictions
    text: You agree to use the Website only for lawful purposes and in accordance with these Terms.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: 'If you register, you agree to: Provide accurate, current, and complete information during registration'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Welldoc
provenance_date: '2026-11-10'
provider_name: Welldoc
provider_slug: welldoc
slug: welldoc-eligibility
source_date: '2026-11-10'
source_filename: welldoc-eligibility.yml
source_heading: Eligibility
source_page: https://www.welldoc.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Welldoc\naid: welldoc\nurl: https://www.welldoc.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for users in the United States. We make no representation that the Website or its\n    content is appropriate or available in other locations.\nentity_types:\n- type: individual\n  text: 'By using the Website, you represent and warrant that: You are at least 18 years of age, or the age of legal\n    majority in your jurisdiction if higher'\n- type: business\n  text: If you are using the Website on behalf of an organization, you represent and warrant\
  \ that you have authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You are not located in a country subject to a U.S. government embargo or designated as a “terrorist supporting”\n    country; You are not listed on any U.S. government list of prohibited or restricted parties;\n- summary: Acceptable use restrictions\n  text: You agree to use the Website only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: 'If you register, you agree to: Provide accurate, current, and complete information during registration'\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age, or the age of legal majority in your jurisdiction if higher\n"
source_yaml_url: https://artifacts.apis.io/welldoc/eligibility/welldoc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Welldoc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Healthcare
- Chronic Care Management
- Diabetes
- Digital Therapeutics
- Cardiometabolic Health
- Artificial Intelligence
- Remote Patient Monitoring
- Medical Device Software
---
