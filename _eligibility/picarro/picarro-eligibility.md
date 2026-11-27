---
api_specs:
- filename: picarro-sam-foup-asyncapi.yml
  format: yaml
  label: Picarro Edge — SAM FOUP gRPC API
  slug: picarro-edge-sam-foup-grpc-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/picarro/asyncapi/picarro-sam-foup-asyncapi.yml
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
  - summary: Impersonation and personal data
    text: Do not reveal any personal information.
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
name: Picarro
provenance_date: '2026-11-10'
provider_name: Picarro
provider_slug: picarro
slug: picarro-eligibility
source_date: '2026-11-10'
source_filename: picarro-eligibility.yml
source_heading: Eligibility
source_page: https://www.picarro.com/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Picarro\naid: picarro\nurl: https://www.picarro.com/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Impersonation and personal data\n  text: Do not reveal any personal information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/picarro/eligibility/picarro-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Picarro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gas Detection
- Environmental Monitoring
- Emissions
- Methane
- Greenhouse Gas
- Scientific Instruments
- Semiconductors
- Industrial IoT
- Sensors
- Analytics
- gRPC
---
