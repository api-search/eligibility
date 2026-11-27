---
api_specs:
- filename: charmshots-com-openapi-generated.yml
  format: yaml
  label: Charmshots API
  slug: charmshots-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmshots-com/openapi/_ae-authored/charmshots-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use the studio for portraits of yourself
    type: individual
  minimum_age:
    text: The dating-photo service is intended for adults.
    value: adults
  restricted_uses:
  - summary: Impersonation and verification evasion
    text: Do not impersonate another person, create deceptive identity material or use generated images to complete verification checks.
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
name: Charmshots
provenance_date: '2026-11-09'
provider_name: Charmshots
provider_slug: charmshots-com
slug: charmshots-com-eligibility
source_date: '2026-11-09'
source_filename: charmshots-com-eligibility.yml
source_heading: Eligibility
source_page: https://charmshots.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Charmshots\naid: charmshots-com\nurl: https://charmshots.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use the studio for portraits of yourself\nrestricted_uses:\n- summary: Impersonation and verification evasion\n  text: Do not impersonate another person, create deceptive identity material or use generated images to complete\n    verification checks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adults\n  text: The dating-photo service is intended for adults.\n"
source_yaml_url: https://artifacts.apis.io/charmshots-com/eligibility/charmshots-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Charmshots's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Photography
- Dating
- Selfie
- Image Generation
---
