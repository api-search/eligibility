---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CERTAIN FEATURES OF THE SERVICES ARE NOT INTENDED FOR USE IN CONNECTICUT, IDAHO, MAINE, NEVADA, OREGON, UTAH, OR WASHINGTON
  entity_types:
  - text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    type: individual
  minimum_age:
    text: the Platform is not intended for use by anyone under the age of eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis or healthcare advice via Baba Companion
    text: Use or attempt to use Baba Companion for the diagnosis of disease or other conditions
  - summary: Not for emergency use
    text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY USE.
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
name: Baba
provenance_date: '2026-11-09'
provider_name: Baba
provider_slug: baba
slug: baba-eligibility
source_date: '2026-11-09'
source_filename: baba-eligibility.yml
source_heading: Eligibility
source_page: https://app.baba.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baba\naid: baba\nurl: https://app.baba.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CERTAIN FEATURES OF THE SERVICES ARE NOT INTENDED FOR USE IN CONNECTICUT, IDAHO, MAINE, NEVADA, OREGON,\n    UTAH, OR WASHINGTON\nentity_types:\n- type: individual\n  text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\nrestricted_uses:\n- summary: Not for diagnosis or healthcare advice via Baba Companion\n  text: Use or attempt to use Baba Companion for the diagnosis of disease or other conditions\n- summary: Not for emergency use\n  text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY USE.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Platform is not intended for use by anyone under the age of eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/baba/eligibility/baba-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Baba's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medicare
- Patient Advocacy
- Care Navigation
- Health Insurance
- Digital Health
---
