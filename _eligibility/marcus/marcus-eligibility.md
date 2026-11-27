---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service may only be used in the United States, including its territories, or on a United States military base.
  entity_types:
  - text: Any natural person using the Service must be at least 18 years of age.
    type: individual
  minimum_age:
    text: BY USING OR ACCESSING THE SERVICE, YOU AFFIRM YOU ARE AT LEAST 18 YEARS OF AGE.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Federal law requires we obtain, verify, and record information that identifies each person who creates a relationship.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Marcus by Goldman Sachs
provenance_date: '2026-11-10'
provider_name: Marcus by Goldman Sachs
provider_slug: marcus
slug: marcus-eligibility
source_date: '2026-11-10'
source_filename: marcus-eligibility.yml
source_heading: Eligibility
source_page: https://www.marcus.com/us/en/site-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Marcus by Goldman Sachs\naid: marcus\nurl: https://www.marcus.com/us/en/site-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service may only be used in the United States, including its territories, or on a United States military\n    base.\nentity_types:\n- type: individual\n  text: Any natural person using the Service must be at least 18 years of age.\nrestricted_uses:\n- summary: Export restrictions\n  text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a U.S. government embargo or\
  \ other restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Federal law requires we obtain, verify, and record information that identifies each person who creates a\n    relationship.\nminimum_age:\n  value: '18'\n  text: BY USING OR ACCESSING THE SERVICE, YOU AFFIRM YOU ARE AT LEAST 18 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/marcus/eligibility/marcus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Marcus by Goldman Sachs's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Consumer Banking
- Neobank
- Digital Banking
- Savings
- Open Finance
---
