---
api_specs:
- filename: appbricx-com-openapi-generated.yml
  format: yaml
  label: Appbricx API
  slug: appbricx-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appbricx-com/openapi/_ae-authored/appbricx-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under the age of majority in your jurisdiction, you must have your parent or legal guardian’s permission.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Generate content that is illegal, deceptive, harassing, hateful, or sexually exploits minors
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
name: Appbricx
provenance_date: '2026-11-09'
provider_name: Appbricx
provider_slug: appbricx-com
slug: appbricx-com-eligibility
source_date: '2026-11-09'
source_filename: appbricx-com-eligibility.yml
source_heading: Eligibility
source_page: https://appbricx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appbricx\naid: appbricx-com\nurl: https://appbricx.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under the age of majority in your jurisdiction,\n    you must have your parent or legal guardian’s permission.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Generate content that is illegal, deceptive, harassing, hateful, or sexually exploits minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/appbricx-com/eligibility/appbricx-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Appbricx's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Development
- Automation
---
