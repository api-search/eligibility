---
api_specs:
- filename: peaka-api-openapi.json
  format: json
  label: Peaka Gateway API API
  slug: peaka-gateway-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peaka/openapi/_original/peaka-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In these Terms & Conditions, "you" refers both to you as an individual and to the entity you represent.
    type: individual
  - text: In these Terms & Conditions, "you" refers both to you as an individual and to the entity you represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Promotions eligibility
    text: Please note that all Promotions may be governed by separate rules that may contain certain eligibility requirements, such as restrictions as to age and geographic location.
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
name: Peaka
provenance_date: '2026-11-10'
provider_name: Peaka
provider_slug: peaka
slug: peaka-eligibility
source_date: '2026-11-10'
source_filename: peaka-eligibility.yml
source_heading: Eligibility
source_page: https://www.peaka.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peaka\naid: peaka\nurl: https://www.peaka.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In these Terms & Conditions, \"you\" refers both to you as an individual and to the entity you represent.\n- type: business\n  text: In these Terms & Conditions, \"you\" refers both to you as an individual and to the entity you represent.\nrestricted_uses:\n- summary: Promotions eligibility\n  text: Please note that all Promotions may be governed by separate rules that may contain certain eligibility requirements,\n \
  \   such as restrictions as to age and geographic location.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/peaka/eligibility/peaka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Peaka's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Integration
- Governance
- Analytics
---
