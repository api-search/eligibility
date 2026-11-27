---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: commercial purposes
    text: access or use for any commercial purposes any part of the Site or any services or materials available through the Site
  - summary: illegal purposes
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law
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
name: Zenflow
provenance_date: '2026-11-10'
provider_name: Zenflow
provider_slug: zenflow
slug: zenflow-eligibility
source_date: '2026-11-10'
source_filename: zenflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenflow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenflow\naid: zenflow\nurl: https://www.zenflow.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\nrestricted_uses:\n- summary: commercial purposes\n  text: access or use for any commercial purposes any part of the Site or any services or materials available through\n    the Site\n- summary: illegal\
  \ purposes\n  text: use the Site for any illegal purpose or in violation of any local, state, national, or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/zenflow/eligibility/zenflow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Zenflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Medical Technology
- Urology
- Implant
- Y Combinator
---
