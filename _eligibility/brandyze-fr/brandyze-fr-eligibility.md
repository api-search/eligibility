---
api_specs:
- filename: brandyze-fr-openapi-generated.yml
  format: yaml
  label: Brandyze API
  slug: brandyze-fr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandyze-fr/openapi/_ae-authored/brandyze-fr-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: particuliers (B2C)
    type: individual
  - text: professionnels (B2B)
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Le Vendeur se réserve le droit de refuser toute inscription et de suspendre tout compte en cas d'usage frauduleux, de fausse déclaration ou de violation des présentes CGV.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brandyze
provenance_date: '2026-11-09'
provider_name: Brandyze
provider_slug: brandyze-fr
slug: brandyze-fr-eligibility
source_date: '2026-11-09'
source_filename: brandyze-fr-eligibility.yml
source_heading: Eligibility
source_page: https://brandyze.fr/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandyze\naid: brandyze-fr\nurl: https://brandyze.fr/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: particuliers (B2C)\n- type: business\n  text: professionnels (B2B)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Le Vendeur se réserve le droit de refuser toute inscription et de suspendre tout compte en cas d'usage frauduleux,\n    de fausse déclaration ou de violation des présentes CGV.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brandyze-fr/eligibility/brandyze-fr-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Brandyze's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Content Generation
- Brand Analysis
- Creator Tools
---
