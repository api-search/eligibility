---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (1) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country; and (2) you are not listed on any U.S. Government list of prohibited or restricted parties.
  entity_types:
  - text: By using the Services, you represent and warrant that, you are a natural person, you are 18 or older
    type: individual
  minimum_age:
    text: The Services are For Use by Individuals 18 Years of Age and Older.
    value: '18'
  restricted_uses:
  - summary: Medical advice reliance
    text: The Services are not a substitute for professional medical advice, diagnosis or treatment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Parts of the Services may be accessed only by registering for an account and creating a password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pluto
provenance_date: '2026-11-10'
provider_name: Pluto
provider_slug: pluto
slug: pluto-eligibility
source_date: '2026-11-10'
source_filename: pluto-eligibility.yml
source_heading: Eligibility
source_page: https://pluto.health/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pluto\naid: pluto\nurl: https://pluto.health/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (1) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a \"terrorist supporting\" country; and (2) you\n    are not listed on any U.S. Government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: By using the Services, you represent and warrant that, you are a natural person, you are 18 or older\nrestricted_uses:\n- summary:\
  \ Medical advice reliance\n  text: The Services are not a substitute for professional medical advice, diagnosis or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Parts of the Services may be accessed only by registering for an account and creating a password.\nminimum_age:\n  value: '18'\n  text: The Services are For Use by Individuals 18 Years of Age and Older.\n"
source_yaml_url: https://artifacts.apis.io/pluto/eligibility/pluto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Pluto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Clinical Intelligence
- Health Data
- Care Coordination
- Digital Health
- Interoperability
---
