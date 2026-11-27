---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    served:
    - US
    text: Use of our Services is currently authorized only in the United States. You represent and warrant that you are not located in, or a resident or a national of, any country or region subject to a U.S. government embargo or other restriction (currently, Cuba, Iran, North Korea, Russia or the Donetsk, Luhansk or Crimea regions of Ukraine)
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You will not export, re-export, transship or otherwise dispose of any Nusano items, including related technology
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'When registering with Nusano, you must: provide true, current and complete information about yourself on the registration form'
excluded_countries:
- CU
- IR
- KP
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nusano
provenance_date: '2026-11-10'
provider_name: Nusano
provider_slug: nusano
slug: nusano-eligibility
source_date: '2026-11-10'
source_filename: nusano-eligibility.yml
source_heading: Eligibility
source_page: https://nusano.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nusano\naid: nusano\nurl: https://nusano.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  text: Use of our Services is currently authorized only in the United States. You represent and warrant that you\n    are not located in, or a resident or a national of, any country or region subject to a U.S. government embargo\n    or other restriction (currently, Cuba, Iran, North Korea, Russia or the Donetsk, Luhansk or Crimea regions of\n    Ukraine)\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our\
  \ Services.\nrestricted_uses:\n- summary: Export restrictions\n  text: You will not export, re-export, transship or otherwise dispose of any Nusano items, including related technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'When registering with Nusano, you must: provide true, current and complete information about yourself on\n    the registration form'\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/nusano/eligibility/nusano-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nusano's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Radioisotopes
- Nuclear Medicine
- Life Sciences
- Healthcare
- Oncology
- Radiopharmaceuticals
- Physics
- Advanced Manufacturing
- Nuclear Energy
- HALEU
- Critical Minerals
---
