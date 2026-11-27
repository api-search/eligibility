---
api_specs:
- filename: toptik-app-openapi-generated.yml
  format: yaml
  label: toptik-app API
  slug: toptik-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toptik-app/openapi/_ae-authored/toptik-app-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use TopTik on behalf of an organisation, you agree on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, harassing or infringing uses
    text: violate any law, including data-protection, privacy, and intellectual-property law
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
name: toptik-app
provenance_date: '2026-11-10'
provider_name: toptik-app
provider_slug: toptik-app
slug: toptik-app-eligibility
source_date: '2026-11-10'
source_filename: toptik-app-eligibility.yml
source_heading: Eligibility
source_page: https://toptik.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: toptik-app\naid: toptik-app\nurl: https://toptik.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use TopTik on behalf of an organisation, you agree on its behalf.\nrestricted_uses:\n- summary: Unlawful, harassing or infringing uses\n  text: violate any law, including data-protection, privacy, and intellectual-property law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toptik-app/eligibility/toptik-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from toptik-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- TikTok
- Data
- Public
---
