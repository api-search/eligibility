---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: AI Plan Creator is run from New Zealand at aiplancreator.com and in our apps.
  entity_types:
  - text: An account is for one person.
    type: individual
  - text: If you use it for an organisation, you agree for that organisation.
    type: business
  minimum_age:
    text: You must be at least 16 to use AI Plan Creator, and an adult (or have a parent's or guardian's permission) to buy anything.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Do not use AI Plan Creator for anything unlawful, harmful, deceptive or infringing.
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
name: AI Plan Creator
provenance_date: '2026-11-09'
provider_name: AI Plan Creator
provider_slug: aiplancreator-com
slug: aiplancreator-com-eligibility
source_date: '2026-11-09'
source_filename: aiplancreator-com-eligibility.yml
source_heading: Eligibility
source_page: https://aiplancreator.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Plan Creator\naid: aiplancreator-com\nurl: https://aiplancreator.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: AI Plan Creator is run from New Zealand at aiplancreator.com and in our apps.\nentity_types:\n- type: individual\n  text: An account is for one person.\n- type: business\n  text: If you use it for an organisation, you agree for that organisation.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Do not use AI Plan Creator for anything unlawful, harmful, deceptive or infringing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 to use AI Plan Creator, and an adult (or have a parent's or guardian's permission)\n    to buy anything.\n"
source_yaml_url: https://artifacts.apis.io/aiplancreator-com/eligibility/aiplancreator-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AI Plan Creator's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Design
- Architecture
- 3D
- New Zealand
---
