---
api_specs:
- filename: caliuapp-com-api-keys-api-openapi.yml
  format: yaml
  label: Caliu API Keys API
  slug: caliuapp-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-api-keys-api-openapi.yml
- filename: caliuapp-com-attachments-api-openapi.yml
  format: yaml
  label: Caliu Attachments API
  slug: caliuapp-com-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-attachments-api-openapi.yml
- filename: caliuapp-com-auth-api-openapi.yml
  format: yaml
  label: Caliu Auth API
  slug: caliuapp-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-auth-api-openapi.yml
- filename: caliuapp-com-devices-api-openapi.yml
  format: yaml
  label: Caliu Devices API
  slug: caliuapp-com-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-devices-api-openapi.yml
- filename: caliuapp-com-export-api-openapi.yml
  format: yaml
  label: Caliu Export API
  slug: caliuapp-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-export-api-openapi.yml
- filename: caliuapp-com-notes-api-openapi.yml
  format: yaml
  label: Caliu Notes API
  slug: caliuapp-com-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-notes-api-openapi.yml
- filename: caliuapp-com-reminders-api-openapi.yml
  format: yaml
  label: Caliu Reminders API
  slug: caliuapp-com-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-reminders-api-openapi.yml
- filename: caliuapp-com-subscription-api-openapi.yml
  format: yaml
  label: Caliu Subscription API
  slug: caliuapp-com-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-subscription-api-openapi.yml
- filename: caliuapp-com-tags-api-openapi.yml
  format: yaml
  label: Caliu Tags API
  slug: caliuapp-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-tags-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use Caliu.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use Caliu.
    value: '16'
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
name: Caliu
provenance_date: '2026-11-09'
provider_name: Caliu
provider_slug: caliuapp-com
slug: caliuapp-com-eligibility
source_date: '2026-11-09'
source_filename: caliuapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://caliuapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caliu\naid: caliuapp-com\nurl: https://caliuapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use Caliu.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Caliu.\n"
source_yaml_url: https://artifacts.apis.io/caliuapp-com/eligibility/caliuapp-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Caliu's own page on 2026-11-09.
synthetic: false
tags:
- Note Taking
- Privacy
- Local-First
- Markdown
- Cross-Platform
---
