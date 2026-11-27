---
api_specs:
- filename: grabmail-io-account-api-openapi.yml
  format: yaml
  label: grabmail-io Account API
  slug: grabmail-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabmail-io/openapi/grabmail-io-account-api-openapi.yml
- filename: grabmail-io-mailbox-api-openapi.yml
  format: yaml
  label: grabmail-io Mailbox API
  slug: grabmail-io-mailbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabmail-io/openapi/grabmail-io-mailbox-api-openapi.yml
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
  - summary: Illegal, harmful or fraudulent use
    text: Nothing illegal, nothing designed to harm another person or service
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Public domains require no account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: grabmail-io
provenance_date: '2026-11-09'
provider_name: grabmail-io
provider_slug: grabmail-io
slug: grabmail-io-eligibility
source_date: '2026-11-09'
source_filename: grabmail-io-eligibility.yml
source_heading: Eligibility
source_page: https://grabmail.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: grabmail-io\naid: grabmail-io\nurl: https://grabmail.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal, harmful or fraudulent use\n  text: Nothing illegal, nothing designed to harm another person or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Public domains require no account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grabmail-io/eligibility/grabmail-io-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from grabmail-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Developer Tools
---
