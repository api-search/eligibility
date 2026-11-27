---
api_specs:
- filename: cashflo-ingest-api-openapi.yml
  format: yaml
  label: CashFlo Ingest API
  slug: cashflo-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cashflo/openapi/cashflo-ingest-api-openapi.yml
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
  - summary: Prohibited uses list
    text: (iii) to violate any international, federal, provincial or state regulations, rules, laws, or applicable ordinances;
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
name: CashFlo
provenance_date: '2026-11-09'
provider_name: CashFlo
provider_slug: cashflo
slug: cashflo-eligibility
source_date: '2026-11-09'
source_filename: cashflo-eligibility.yml
source_heading: Eligibility
source_page: https://www.cashflo.io/tnc/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CashFlo\naid: cashflo\nurl: https://www.cashflo.io/tnc/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses list\n  text: (iii) to violate any international, federal, provincial or state regulations, rules, laws, or applicable\n    ordinances;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cashflo/eligibility/cashflo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CashFlo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounts Payable
- Payments
- Working Capital
- Supply Chain Finance
- ERP Integration
- Compliance
- India
---
