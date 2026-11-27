---
api_specs:
- filename: termius-group-api-openapi.yml
  format: yaml
  label: Termius Group API
  slug: termius-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termius/openapi/termius-group-api-openapi.yml
- filename: termius-host-api-openapi.yml
  format: yaml
  label: Termius Host API
  slug: termius-host-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termius/openapi/termius-host-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you created an account using an email address belonging to your employer or other entity, you represent and warrant that you have the authority to create an account on behalf of such entity
    type: business
  minimum_age:
    text: null
    value: null
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
name: Termius
provenance_date: '2026-11-10'
provider_name: Termius
provider_slug: termius
slug: termius-eligibility
source_date: '2026-11-10'
source_filename: termius-eligibility.yml
source_heading: Eligibility
source_page: https://termius.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Termius\naid: termius\nurl: https://termius.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you created an account using an email address belonging to your employer or other entity, you represent\n    and warrant that you have the authority to create an account on behalf of such entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/termius/eligibility/termius-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Termius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- SSH
- SSH Client
- Terminal
- Developer Tools
- DevOps
- Infrastructure
- Security
- Remote Access
---
