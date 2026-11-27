---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country.
  entity_types:
  - text: You must be at least 13 years of age, or at least 18 years of age to enroll in the Messaging Program.
    type: individual
  - text: If you use our Services on behalf of another person or entity, (a) all references to "you" throughout these Terms will include that person or entity
    type: business
  minimum_age:
    text: You must be at least 13 years of age, or at least 18 years of age to enroll in the Messaging Program.
    value: '13'
  restricted_uses:
  - summary: Sanctioned or restricted parties
    text: You must not be listed on any United States government list of prohibited or restricted parties.
  - summary: Account transfer or gifting
    text: Users do not own their accounts, and gifting or otherwise transferring of accounts or access keys is prohibited.
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
name: Atari
provenance_date: '2026-11-09'
provider_name: Atari
provider_slug: atari
slug: atari-eligibility
source_date: '2026-11-09'
source_filename: atari-eligibility.yml
source_heading: Eligibility
source_page: https://atari.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atari\naid: atari\nurl: https://atari.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You must not be located in a country that is subject to the United States government embargo, or that has\n    been designated by the United States government as a \"terrorist supporting\" country.\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age, or at least 18 years of age to enroll in the Messaging Program.\n- type: business\n  text: If you use our Services on behalf of another person or entity, (a) all references\
  \ to \"you\" throughout these\n    Terms will include that person or entity\nrestricted_uses:\n- summary: Sanctioned or restricted parties\n  text: You must not be listed on any United States government list of prohibited or restricted parties.\n- summary: Account transfer or gifting\n  text: Users do not own their accounts, and gifting or otherwise transferring of accounts or access keys is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age, or at least 18 years of age to enroll in the Messaging Program.\n"
source_yaml_url: https://artifacts.apis.io/atari/eligibility/atari-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Atari's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Games
- Gaming
- Consumer Hardware
- Entertainment
- Consoles
- Retro Gaming
- Media
---
