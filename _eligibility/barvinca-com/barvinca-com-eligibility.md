---
api_specs:
- filename: barvinca-com-openapi-generated.yml
  format: yaml
  label: Barvinca API
  slug: barvinca-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barvinca-com/openapi/_ae-authored/barvinca-com-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that organization to these Terms.
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
name: Barvinca
provenance_date: '2026-11-09'
provider_name: Barvinca
provider_slug: barvinca-com
slug: barvinca-com-eligibility
source_date: '2026-11-09'
source_filename: barvinca-com-eligibility.yml
source_heading: Eligibility
source_page: https://barvinca.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barvinca\naid: barvinca-com\nurl: https://barvinca.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/barvinca-com/eligibility/barvinca-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Barvinca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- BulkUserManagement
- Autodesk
- BIM360
- Automation
---
