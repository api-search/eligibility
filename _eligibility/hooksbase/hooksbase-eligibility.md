---
api_specs:
- filename: hooksbase-openapi-generated.yml
  format: yaml
  label: Hooksbase API
  slug: hooksbase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hooksbase/openapi/_ae-authored/hooksbase-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated or sensitive data
    text: Do not send regulated, highly sensitive, or prohibited data unless your agreement with Hooksbase and your own compliance review allow that use.
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
name: Hooksbase
provenance_date: '2026-11-09'
provider_name: Hooksbase
provider_slug: hooksbase
slug: hooksbase-eligibility
source_date: '2026-11-09'
source_filename: hooksbase-eligibility.yml
source_heading: Eligibility
source_page: https://www.hooksbase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hooksbase\naid: hooksbase\nurl: https://www.hooksbase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulated or sensitive data\n  text: Do not send regulated, highly sensitive, or prohibited data unless your agreement with Hooksbase and your\n    own compliance review allow that use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hooksbase/eligibility/hooksbase-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Hooksbase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event Infrastructure
- Artificial Intelligence
- Webhook
- Automation
- Integration
---
