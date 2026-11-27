---
api_specs:
- filename: markifact-com-connections-api-openapi.yml
  format: yaml
  label: markifact-com Connections API
  slug: markifact-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-connections-api-openapi.yml
- filename: markifact-com-credits-api-openapi.yml
  format: yaml
  label: markifact-com Credits API
  slug: markifact-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-credits-api-openapi.yml
- filename: markifact-com-logs-api-openapi.yml
  format: yaml
  label: markifact-com Logs API
  slug: markifact-com-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-logs-api-openapi.yml
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
  - summary: Illegal tracking or phishing
    text: Use the Service for illegal tracking, phishing, or deceptive practices
  - summary: Spam
    text: Send spam or unsolicited communications through our Service
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
name: markifact-com
provenance_date: '2026-11-10'
provider_name: markifact-com
provider_slug: markifact-com
slug: markifact-com-eligibility
source_date: '2026-11-10'
source_filename: markifact-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.markifact.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: markifact-com\naid: markifact-com\nurl: https://www.markifact.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal tracking or phishing\n  text: Use the Service for illegal tracking, phishing, or deceptive practices\n- summary: Spam\n  text: Send spam or unsolicited communications through our Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/markifact-com/eligibility/markifact-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from markifact-com's own page on 2026-11-10.
synthetic: false
tags:
- AI Marketing Automation
- Ad Management
- Reporting
- Workflow Automation
- Marketing Operations
- Data Integration
---
