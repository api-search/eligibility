---
api_specs:
- filename: termscout-contract-positions-api-openapi.yml
  format: yaml
  label: TermScout Contract Positions API
  slug: termscout-contract-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termscout/openapi/termscout-contract-positions-api-openapi.yml
- filename: termscout-contracts-api-openapi.yml
  format: yaml
  label: TermScout Contracts API
  slug: termscout-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termscout/openapi/termscout-contracts-api-openapi.yml
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
  - summary: No providing services to third parties
    text: (f) use the Services to provide any service to a third party without first obtaining a separate service provider license to do so from TermScout.
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
name: TermScout
provenance_date: '2026-11-10'
provider_name: TermScout
provider_slug: termscout
slug: termscout-eligibility
source_date: '2026-11-10'
source_filename: termscout-eligibility.yml
source_heading: Eligibility
source_page: https://www.termscout.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TermScout\naid: termscout\nurl: https://www.termscout.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No providing services to third parties\n  text: (f) use the Services to provide any service to a third party without first obtaining a separate service\n    provider license to do so from TermScout.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/termscout/eligibility/termscout-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TermScout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal Tech
- Contract Intelligence
- Contract Certification
- Contract Analysis
- Procurement
- Legal Operations
- Sales Enablement
- Artificial Intelligence
- Contract Data
- Document Analysis
---
