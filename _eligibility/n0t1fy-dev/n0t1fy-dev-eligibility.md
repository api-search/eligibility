---
api_specs:
- filename: n0t1fy-dev-health-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Health API
  slug: n0t1fy-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-health-api-openapi.yml
- filename: n0t1fy-dev-keys-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Keys API
  slug: n0t1fy-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-keys-api-openapi.yml
- filename: n0t1fy-dev-messages-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Messages API
  slug: n0t1fy-dev-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-messages-api-openapi.yml
- filename: n0t1fy-dev-verifications-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Verifications API
  slug: n0t1fy-dev-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-verifications-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GE
    text: Developer-first transactional SMS for Georgia.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content under Georgian law
    text: Content that is unlawful under Georgian law, or that harasses or threatens the recipient.
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
name: n0t1fy-dev
provenance_date: '2026-11-10'
provider_name: n0t1fy-dev
provider_slug: n0t1fy-dev
slug: n0t1fy-dev-eligibility
source_date: '2026-11-10'
source_filename: n0t1fy-dev-eligibility.yml
source_heading: Eligibility
source_page: https://n0t1fy.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: n0t1fy-dev\naid: n0t1fy-dev\nurl: https://n0t1fy.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GE\n  excluded: []\n  text: Developer-first transactional SMS for Georgia.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful content under Georgian law\n  text: Content that is unlawful under Georgian law, or that harasses or threatens the recipient.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/n0t1fy-dev/eligibility/n0t1fy-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from n0t1fy-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Georgia
- Transactional
---
