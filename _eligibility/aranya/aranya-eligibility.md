---
api_specs:
- filename: aranya-openapi-generated.yml
  format: yaml
  label: Aranya API
  slug: aranya-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aranya/openapi/_ae-authored/aranya-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are for business use.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract to use them.
    value: '18'
  restricted_uses:
  - summary: Violating law or third-party rights
    text: Use the Services in violation of any law or third-party rights
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
name: Aranya
provenance_date: '2026-11-09'
provider_name: Aranya
provider_slug: aranya
slug: aranya-eligibility
source_date: '2026-11-09'
source_filename: aranya-eligibility.yml
source_heading: Eligibility
source_page: https://aranya.tech/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aranya\naid: aranya\nurl: https://aranya.tech/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are for business use.\nrestricted_uses:\n- summary: Violating law or third-party rights\n  text: Use the Services in violation of any law or third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract to use them.\n"
source_yaml_url: https://artifacts.apis.io/aranya/eligibility/aranya-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aranya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Cloud
- Edge
- Automation
---
