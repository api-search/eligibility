---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Private individuals who purchase the app independently via app stores
    type: individual
  - text: Rehabilitation clinics conclude a separate B2B license agreement with nyra health.
    type: business
  minimum_age:
    text: Independent registration requires legal age and full legal capacity.
    value: legal age
  restricted_uses:
  - summary: Not a substitute for medical care
    text: The myReha app and nyra insights are not a substitute for a medical examination or medical or health advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Successful verification of insurance eligibility
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NyraHealth
provenance_date: '2026-11-10'
provider_name: NyraHealth
provider_slug: nyrahealth
slug: nyrahealth-eligibility
source_date: '2026-11-10'
source_filename: nyrahealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.nyra.health/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NyraHealth\naid: nyrahealth\nurl: https://www.nyra.health/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Private individuals who purchase the app independently via app stores\n- type: business\n  text: Rehabilitation clinics conclude a separate B2B license agreement with nyra health.\nrestricted_uses:\n- summary: Not a substitute for medical care\n  text: The myReha app and nyra insights are not a substitute for a medical examination or medical or health advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Successful verification of insurance eligibility\nminimum_age:\n  value: legal age\n  text: Independent registration requires legal age and full legal capacity.\n"
source_yaml_url: https://artifacts.apis.io/nyrahealth/eligibility/nyrahealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from NyraHealth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Neurotherapy
- Digital Health
- Healthcare
---
