---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not intend for the Website to be used by persons or entities in countries or jurisdictions that require us to obtain a registration or license.
  entity_types:
  - text: acting in your capacity as an employee or other representative of your company or other entity, if applicable
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Money laundering or terrorism financing
    text: you will not use the Website in connection with money laundering or the financing of terrorism.
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
name: Sensorum Health
provenance_date: '2026-11-10'
provider_name: Sensorum Health
provider_slug: sensorum-health
slug: sensorum-health-eligibility
source_date: '2026-11-10'
source_filename: sensorum-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.sensorum.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sensorum Health\naid: sensorum-health\nurl: https://www.sensorum.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not intend for the Website to be used by persons or entities in countries or jurisdictions that require\n    us to obtain a registration or license.\nentity_types:\n- type: business\n  text: acting in your capacity as an employee or other representative of your company or other entity, if applicable\nrestricted_uses:\n- summary: Money laundering or terrorism financing\n  text: you will not use the Website in connection with money laundering or the\
  \ financing of terrorism.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/sensorum-health/eligibility/sensorum-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sensorum Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Health
- Remote Patient Monitoring
- Digital Health
- Elderly Care
- Sensors
- Chronic Care
---
