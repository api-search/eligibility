---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Client represents that it is not located in, or a national or resident of, an embargoed country, and is not on any U.S. government list of restricted or prohibited parties.
  entity_types:
  - text: If you accept on behalf of an entity, you represent that you have authority to bind that entity, and “Client” refers to that entity.
    type: business
  - text: U.S. Government users receive only the rights granted to all other Clients
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: Client will comply with applicable export control and economic sanctions laws
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
name: Foreman
provenance_date: '2026-11-09'
provider_name: Foreman
provider_slug: foreman
slug: foreman-eligibility
source_date: '2026-11-09'
source_filename: foreman-eligibility.yml
source_heading: Eligibility
source_page: https://foreman.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foreman\naid: foreman\nurl: https://foreman.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Client represents that it is not located in, or a national or resident of, an embargoed country, and is\n    not on any U.S. government list of restricted or prohibited parties.\nentity_types:\n- type: business\n  text: If you accept on behalf of an entity, you represent that you have authority to bind that entity, and “Client”\n    refers to that entity.\n- type: government\n  text: U.S. Government users receive only the rights granted to all other Clients\nrestricted_uses:\n- summary:\
  \ Export and sanctions compliance\n  text: Client will comply with applicable export control and economic sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/foreman/eligibility/foreman-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Foreman's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Project Management
- Estimating
- Invoicing
- Scheduling
- Contractors
- Artificial Intelligence
---
