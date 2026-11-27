---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Use the Service if You are located in a country embargoed by the United States or if You are on the U.S. Treasury Department’s list of Specially Designated Nationals;
  entity_types:
  - text: To use the Service, You must be a natural person, at least 18 years old, who is assigned to the e-mail address or Facebook Login
    type: individual
  minimum_age:
    text: You must be a natural person, at least 18 years old
    value: '18'
  restricted_uses:
  - summary: M life program restricted to 21+
    text: ACCESS TO THE MGM RESORTS INTERNATIONAL M LIFE PROGRAM (AS FURTHER DESCRIBED BELOW) IS RESTRICTED TO PERSONS WHO ARE 21 YEARS OF AGE OR OLDER.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: At our sole discretion, we may require proof that You meet this condition in connection with Your use of the Service.
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PLAYSTUDIOS
provenance_date: '2026-11-10'
provider_name: PLAYSTUDIOS
provider_slug: playstudios
slug: playstudios-eligibility
source_date: '2026-11-10'
source_filename: playstudios-eligibility.yml
source_heading: Eligibility
source_page: https://www.playstudios.com/terms-of-service-mobile/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PLAYSTUDIOS\naid: playstudios\nurl: https://www.playstudios.com/terms-of-service-mobile/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Use the Service if You are located in a country embargoed by the United States or if You are on the U.S.\n    Treasury Department’s list of Specially Designated Nationals;\nentity_types:\n- type: individual\n  text: To use the Service, You must be a natural person, at least 18 years old, who is assigned to the e-mail address\n    or Facebook Login\nrestricted_uses:\n- summary: M life program restricted to 21+\n  text: ACCESS\
  \ TO THE MGM RESORTS INTERNATIONAL M LIFE PROGRAM (AS FURTHER DESCRIBED BELOW) IS RESTRICTED TO PERSONS\n    WHO ARE 21 YEARS OF AGE OR OLDER.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: At our sole discretion, we may require proof that You meet this condition in connection with Your use of\n    the Service.\nminimum_age:\n  value: '18'\n  text: You must be a natural person, at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/playstudios/eligibility/playstudios-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from PLAYSTUDIOS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Mobile Games
- Casual Games
- Loyalty
- Rewards
- Entertainment
---
