---
api_specs:
- filename: collective2-autotrade-api-openapi.yml
  format: yaml
  label: Collective2 Autotrade API
  slug: collective2-autotrade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collective2/openapi/collective2-autotrade-api-openapi.yml
- filename: collective2-general-api-openapi.yml
  format: yaml
  label: Collective2 General API
  slug: collective2-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collective2/openapi/collective2-general-api-openapi.yml
- filename: collective2-strategies-api-openapi.yml
  format: yaml
  label: Collective2 Strategies API
  slug: collective2-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collective2/openapi/collective2-strategies-api-openapi.yml
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
    text: We may refuse registration, require additional verification, or suspend or terminate accounts that are incomplete, inaccurate, misleading, fraudulent, or otherwise create legal, compliance, operational, or security risk.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Collective2
provenance_date: '2026-11-09'
provider_name: Collective2
provider_slug: collective2
slug: collective2-eligibility
source_date: '2026-11-09'
source_filename: collective2-eligibility.yml
source_heading: Eligibility
source_page: https://collective2.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collective2\naid: collective2\nurl: https://collective2.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse registration, require additional verification, or suspend or terminate accounts that are incomplete,\n    inaccurate, misleading, fraudulent, or otherwise create legal, compliance, operational, or security risk.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/collective2/eligibility/collective2-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Collective2's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Marketplace
- Investment
---
