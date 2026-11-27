---
api_specs:
- filename: vulk-dev-models-api-openapi.yml
  format: yaml
  label: vulk-dev Models API
  slug: vulk-dev-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-models-api-openapi.yml
- filename: vulk-dev-operations-api-openapi.yml
  format: yaml
  label: vulk-dev Operations API
  slug: vulk-dev-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-operations-api-openapi.yml
- filename: vulk-dev-pay-as-you-go-previous-vulk-api-openapi.yml
  format: yaml
  label: vulk-dev Pay-as-you-go (previous VULK) API
  slug: vulk-dev-pay-as-you-go-previous-vulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-pay-as-you-go-previous-vulk-api-openapi.yml
- filename: vulk-dev-projects-api-openapi.yml
  format: yaml
  label: vulk-dev Projects API
  slug: vulk-dev-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-projects-api-openapi.yml
- filename: vulk-dev-usage-api-openapi.yml
  format: yaml
  label: vulk-dev Usage API
  slug: vulk-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-usage-api-openapi.yml
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
  - summary: Sanctions and illegal activity
    text: Violations of OFAC / EU sanctions regimes
  - summary: Illegal activities and malware
    text: Involvement in hacking, spamming, piracy, or illegal activities
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
name: vulk-dev
provenance_date: '2026-11-10'
provider_name: vulk-dev
provider_slug: vulk-dev
slug: vulk-dev-eligibility
source_date: '2026-11-10'
source_filename: vulk-dev-eligibility.yml
source_heading: Eligibility
source_page: https://vulk.dev/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vulk-dev\naid: vulk-dev\nurl: https://vulk.dev/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctions and illegal activity\n  text: Violations of OFAC / EU sanctions regimes\n- summary: Illegal activities and malware\n  text: Involvement in hacking, spamming, piracy, or illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vulk-dev/eligibility/vulk-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from vulk-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- App Builder
- No-Code
- 3D
---
