---
api_specs:
- filename: b2bhint-com-openapi-generated.yml
  format: yaml
  label: B2BHint API
  slug: b2bhint-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b2bhint-com/openapi/_ae-authored/b2bhint-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: No commercial usage without agreement
    text: Except as otherwise expressly permitted by additional agreement, we do not permit commercial usage of any of our services or APIs.
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
name: B2BHint
provenance_date: '2026-11-09'
provider_name: B2BHint
provider_slug: b2bhint-com
slug: b2bhint-com-eligibility
source_date: '2026-11-09'
source_filename: b2bhint-com-eligibility.yml
source_heading: Eligibility
source_page: https://b2bhint.com/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: B2BHint\naid: b2bhint-com\nurl: https://b2bhint.com/en/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial usage without agreement\n  text: Except as otherwise expressly permitted by additional agreement, we do not permit commercial usage of any\n    of our services or APIs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/b2bhint-com/eligibility/b2bhint-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from B2BHint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Intelligence
- Data
- Finance
- Jurisdictions
---
