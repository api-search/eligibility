---
api_specs:
- filename: clara-cc-openapi-generated.yml
  format: yaml
  label: Clara API
  slug: clara-cc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clara-cc/openapi/_ae-authored/clara-cc-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Clara Global is also offered in other markets listed on the page (AR, CL, PA, PE, UY, BO, CR, DO, EC, GT, PY) but the terms do not state country eligibility.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud and unlawful activity
    text: Use the Service for purposes of fraud, simulation of expenses or transactions, money laundering, terrorist financing or any other activity prohibited by applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Clara may request additional information or documentation from the Client in order to identify it or verify its registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clara
provenance_date: '2026-11-09'
provider_name: Clara
provider_slug: clara-cc
slug: clara-cc-eligibility
source_date: '2026-11-09'
source_filename: clara-cc-eligibility.yml
source_heading: Eligibility
source_page: https://www.clara.com/global/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clara\naid: clara-cc\nurl: https://www.clara.com/global/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Clara Global is also offered in other markets listed on the page (AR, CL, PA, PE, UY, BO, CR, DO, EC, GT,\n    PY) but the terms do not state country eligibility.\nentity_types: []\nrestricted_uses:\n- summary: Fraud and unlawful activity\n  text: Use the Service for purposes of fraud, simulation of expenses or transactions, money laundering, terrorist\n    financing or any other activity prohibited by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Clara may request additional information or documentation from the Client in order to identify it or verify\n    its registration.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clara-cc/eligibility/clara-cc-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Clara's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Spend Management
- Corporate Cards
- Latin America
- Artificial Intelligence
---
