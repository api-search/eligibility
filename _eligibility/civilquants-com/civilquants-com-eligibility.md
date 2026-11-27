---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a legally binding contract under the law of your country of residence to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Free-tier outputs as client deliverables
    text: Free-tier outputs must not be submitted to clients, employers, tendering authorities, regulators, adjudicators, or any other third party as project deliverables
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For paid tiers other than the modular per-calculator product and the 7-day pass, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CivilQuants
provenance_date: '2026-11-09'
provider_name: CivilQuants
provider_slug: civilquants-com
slug: civilquants-com-eligibility
source_date: '2026-11-09'
source_filename: civilquants-com-eligibility.yml
source_heading: Eligibility
source_page: https://civilquants.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CivilQuants\naid: civilquants-com\nurl: https://civilquants.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a legally binding contract under the law of your country\n    of residence to use the Service.\nrestricted_uses:\n- summary: Free-tier outputs as client deliverables\n  text: Free-tier outputs must not be submitted to clients, employers, tendering authorities, regulators, adjudicators,\n    or any other third party as project deliverables\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: For paid tiers other than the modular per-calculator product and the 7-day pass, you must create an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/civilquants-com/eligibility/civilquants-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CivilQuants's own page on 2026-11-09.
synthetic: false
tags:
- Civil Engineering
- Quantity Surveying
- Software
- Software-as-a-Service
- Construction
---
