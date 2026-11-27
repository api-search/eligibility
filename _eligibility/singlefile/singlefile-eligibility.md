---
api_specs:
- filename: singlefile-documents-api-openapi.yml
  format: yaml
  label: SingleFile Documents API
  slug: singlefile-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-documents-api-openapi.yml
- filename: singlefile-entities-api-openapi.yml
  format: yaml
  label: SingleFile Entities API
  slug: singlefile-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-entities-api-openapi.yml
- filename: singlefile-jurisdictions-api-openapi.yml
  format: yaml
  label: SingleFile Jurisdictions API
  slug: singlefile-jurisdictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-jurisdictions-api-openapi.yml
- filename: singlefile-orders-api-openapi.yml
  format: yaml
  label: SingleFile Orders API
  slug: singlefile-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-orders-api-openapi.yml
- filename: singlefile-organizations-api-openapi.yml
  format: yaml
  label: SingleFile Organizations API
  slug: singlefile-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-organizations-api-openapi.yml
- filename: singlefile-schemas-api-openapi.yml
  format: yaml
  label: SingleFile Schemas API
  slug: singlefile-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-schemas-api-openapi.yml
- filename: singlefile-tasks-api-openapi.yml
  format: yaml
  label: SingleFile Tasks API
  slug: singlefile-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/singlefile/openapi/singlefile-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a contract between you or the business entity you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or deceptive activities
    text: Engage in deceptive or illegal activities (including, “spoofing”, “phishing” or pyramid or similar schemes)
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
name: SingleFile
provenance_date: '2026-11-10'
provider_name: SingleFile
provider_slug: singlefile
slug: singlefile-eligibility
source_date: '2026-11-10'
source_filename: singlefile-eligibility.yml
source_heading: Eligibility
source_page: https://www.singlefile.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SingleFile\naid: singlefile\nurl: https://www.singlefile.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a contract between you or the business entity you represent\nrestricted_uses:\n- summary: Illegal or deceptive activities\n  text: Engage in deceptive or illegal activities (including, “spoofing”, “phishing” or pyramid or similar schemes)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/singlefile/eligibility/singlefile-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from SingleFile's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Legal
- Entity Management
- Corporate Compliance
- Registered Agent
- Business Filings
- Regulatory
- Webhook
- OAuth
- Authentication
---
