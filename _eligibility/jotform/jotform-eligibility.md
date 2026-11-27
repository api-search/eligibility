---
api_specs:
- filename: jotform-folder-api-openapi.yml
  format: yaml
  label: Jotform Folder API
  slug: jotform-folder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-folder-api-openapi.yml
- filename: jotform-form-api-openapi.yml
  format: yaml
  label: Jotform Form API
  slug: jotform-form-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-form-api-openapi.yml
- filename: jotform-label-api-openapi.yml
  format: yaml
  label: Jotform Label API
  slug: jotform-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-label-api-openapi.yml
- filename: jotform-report-api-openapi.yml
  format: yaml
  label: Jotform Report API
  slug: jotform-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-report-api-openapi.yml
- filename: jotform-submission-api-openapi.yml
  format: yaml
  label: Jotform Submission API
  slug: jotform-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-submission-api-openapi.yml
- filename: jotform-system-api-openapi.yml
  format: yaml
  label: Jotform System API
  slug: jotform-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-system-api-openapi.yml
- filename: jotform-user-api-openapi.yml
  format: yaml
  label: Jotform User API
  slug: jotform-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-user-api-openapi.yml
- filename: jotform-webhook-api-openapi.yml
  format: yaml
  label: Jotform Webhook API
  slug: jotform-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jotform/openapi/jotform-webhook-api-openapi.yml
claim_count: 2
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
  - summary: Highly sensitive personal data collection
    text: Collecting highly sensitive personal information such as social security numbers, national ID cards or numbers, and the like, without what we deem to be a valid reason for doing so
  - summary: Pornographic content
    text: Gathering, collecting, or asking for or suggesting that form submitters provide pornographic or sexually explicit content
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
name: Jotform
provenance_date: '2026-11-09'
provider_name: Jotform
provider_slug: jotform
slug: jotform-eligibility
source_date: '2026-11-09'
source_filename: jotform-eligibility.yml
source_heading: Eligibility
source_page: https://www.jotform.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jotform\naid: jotform\nurl: https://www.jotform.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Highly sensitive personal data collection\n  text: Collecting highly sensitive personal information such as social security numbers, national ID cards or numbers,\n    and the like, without what we deem to be a valid reason for doing so\n- summary: Pornographic content\n  text: Gathering, collecting, or asking for or suggesting that form submitters provide pornographic or sexually\n    explicit content\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jotform/eligibility/jotform-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Jotform's own page on 2026-11-09.
synthetic: false
tags:
- Forms
- Surveys
- No-Code
- Data Collection
- Workflows
- HIPAA
- EU
- MCP
- E-Signature
- Webhook
- Online Payments
---
