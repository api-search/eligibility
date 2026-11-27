---
api_specs:
- filename: worthune-openapi-generated.yml
  format: yaml
  label: Worthune API
  slug: worthune-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worthune/openapi/_ae-authored/worthune-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization, and “you” means that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal data via stateless endpoints
    text: do not submit data identifying a specific individual through the stateless model endpoints.
  - summary: Embed tokens only for authorized viewers
    text: issue them only for viewers authorized to see that household’s data.
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
name: Worthune
provenance_date: '2026-11-10'
provider_name: Worthune
provider_slug: worthune
slug: worthune-eligibility
source_date: '2026-11-10'
source_filename: worthune-eligibility.yml
source_heading: Eligibility
source_page: https://worthune.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worthune\naid: worthune\nurl: https://worthune.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization, and “you” means that organization.\nrestricted_uses:\n- summary: No personal data via stateless endpoints\n  text: do not submit data identifying a specific individual through the stateless model endpoints.\n- summary: Embed tokens only for authorized viewers\n  text: issue them only for viewers authorized to\
  \ see that household’s data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/worthune/eligibility/worthune-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Worthune's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- WealthTech
- Platform
---
