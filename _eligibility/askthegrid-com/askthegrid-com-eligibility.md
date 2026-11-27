---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use the service.
    type: individual
  - text: If you use it on behalf of an organization, you represent that you are authorized to accept these terms for that organization, and “you” includes it.
    type: business
  - text: If you use the service in your official capacity for a United States federal, state, or local government entity, these terms are an agreement with that entity, not with you personally.
    type: government
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the service.
    value: '18'
  restricted_uses:
  - summary: Acceptable use per Usage Policy
    text: Your use of the service must follow our Usage Policy , which is part of these terms.
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
name: Ask the Grid
provenance_date: '2026-11-09'
provider_name: Ask the Grid
provider_slug: askthegrid-com
slug: askthegrid-com-eligibility
source_date: '2026-11-09'
source_filename: askthegrid-com-eligibility.yml
source_heading: Eligibility
source_page: https://askthegrid.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ask the Grid\naid: askthegrid-com\nurl: https://askthegrid.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the service.\n- type: business\n  text: If you use it on behalf of an organization, you represent that you are authorized to accept these terms\n    for that organization, and “you” includes it.\n- type: government\n  text: If you use the service in your official capacity for a United States federal, state, or local government\n    entity, these\
  \ terms are an agreement with that entity, not with you personally.\nrestricted_uses:\n- summary: Acceptable use per Usage Policy\n  text: Your use of the service must follow our Usage Policy , which is part of these terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the service.\n"
source_yaml_url: https://artifacts.apis.io/askthegrid-com/eligibility/askthegrid-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ask the Grid's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Data
- Mapping
- Real-Time
- Analytics
---
