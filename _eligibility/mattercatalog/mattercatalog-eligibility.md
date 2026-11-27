---
api_specs:
- filename: mattercatalog-openapi-generated.yml
  format: yaml
  label: MatterCatalog API
  slug: mattercatalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattercatalog/openapi/_ae-authored/mattercatalog-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: not stated
  restricted_uses:
  - summary: Unapproved commercial use
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: MatterCatalog
provenance_date: '2026-11-10'
provider_name: MatterCatalog
provider_slug: mattercatalog
slug: mattercatalog-eligibility
source_date: '2026-11-10'
source_filename: mattercatalog-eligibility.yml
source_heading: Eligibility
source_page: https://mattercatalog.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MatterCatalog\naid: mattercatalog\nurl: https://mattercatalog.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unapproved commercial use\n  text: The Site may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: not stated\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/mattercatalog/eligibility/mattercatalog-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from MatterCatalog's own page on 2026-11-10.
synthetic: false
tags:
- Matter
- Smart Home
- IoT
- Certification
- Directory
---
