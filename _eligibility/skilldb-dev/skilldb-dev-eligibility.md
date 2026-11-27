---
api_specs:
- filename: skilldb-dev-openapi-generated.yml
  format: yaml
  label: skilldb-dev API
  slug: skilldb-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skilldb-dev/openapi/_ae-authored/skilldb-dev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Community conduct rules
    text: No harassment, discrimination, or abusive content
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
name: skilldb-dev
provenance_date: '2026-11-10'
provider_name: skilldb-dev
provider_slug: skilldb-dev
slug: skilldb-dev-eligibility
source_date: '2026-11-10'
source_filename: skilldb-dev-eligibility.yml
source_heading: Eligibility
source_page: https://skilldb.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: skilldb-dev\naid: skilldb-dev\nurl: https://skilldb.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization.\nrestricted_uses:\n- summary: Community conduct rules\n  text: No harassment, discrimination, or abusive content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skilldb-dev/eligibility/skilldb-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from skilldb-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Skills
- Catalog
- Developer Tools
- Open Source
---
