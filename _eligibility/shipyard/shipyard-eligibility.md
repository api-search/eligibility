---
api_specs:
- filename: shipyard-openapi-generated.yml
  format: yaml
  label: Shipyard API
  slug: shipyard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipyard/openapi/_ae-authored/shipyard-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: these Terms of Service constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Competing use
    text: use the Site as part of any effort to compete with us
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
name: Shipyard
provenance_date: '2026-11-10'
provider_name: Shipyard
provider_slug: shipyard
slug: shipyard-eligibility
source_date: '2026-11-10'
source_filename: shipyard-eligibility.yml
source_heading: Eligibility
source_page: https://shipyard.build/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shipyard\naid: shipyard\nurl: https://shipyard.build/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: these Terms of Service constitute a legally binding agreement made between you, whether personally or on\n    behalf of an entity\nrestricted_uses:\n- summary: Competing use\n  text: use the Site as part of any effort to compete\
  \ with us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/shipyard/eligibility/shipyard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Shipyard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ephemeral Environments
- CI/CD
- DevOps
- AI Agents
---
