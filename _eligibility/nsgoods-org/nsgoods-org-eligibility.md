---
api_specs:
- filename: nsgoods-org-health-api-openapi.yml
  format: yaml
  label: nsgoods-org Health API
  slug: nsgoods-org-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nsgoods-org/openapi/nsgoods-org-health-api-openapi.yml
- filename: nsgoods-org-payable-api-openapi.yml
  format: yaml
  label: nsgoods-org Payable API
  slug: nsgoods-org-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nsgoods-org/openapi/nsgoods-org-payable-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: No accounts, no subscriptions except the watchdog service which covers the period stated at purchase.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: nsgoods-org
provenance_date: '2026-11-10'
provider_name: nsgoods-org
provider_slug: nsgoods-org
slug: nsgoods-org-eligibility
source_date: '2026-11-10'
source_filename: nsgoods-org-eligibility.yml
source_heading: Eligibility
source_page: https://x402.nsgoods.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: nsgoods-org\naid: nsgoods-org\nurl: https://x402.nsgoods.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: No accounts, no subscriptions except the watchdog service which covers the period stated at purchase.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nsgoods-org/eligibility/nsgoods-org-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from nsgoods-org's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Blockchain
- Data
- Services
- Company
---
