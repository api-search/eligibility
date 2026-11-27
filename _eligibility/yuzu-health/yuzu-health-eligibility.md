---
api_specs:
- filename: yuzu-health-accumulator-experimental-api-openapi.yml
  format: yaml
  label: Yuzu Health Accumulator (Experimental) API
  slug: yuzu-health-accumulator-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-accumulator-experimental-api-openapi.yml
- filename: yuzu-health-benefits-api-openapi.yml
  format: yaml
  label: Yuzu Health Benefits API
  slug: yuzu-health-benefits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-benefits-api-openapi.yml
- filename: yuzu-health-coverage-api-openapi.yml
  format: yaml
  label: Yuzu Health Coverage API
  slug: yuzu-health-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-coverage-api-openapi.yml
- filename: yuzu-health-enrollment-api-openapi.yml
  format: yaml
  label: Yuzu Health Enrollment API
  slug: yuzu-health-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-enrollment-api-openapi.yml
- filename: yuzu-health-eob-experimental-api-openapi.yml
  format: yaml
  label: Yuzu Health EOB (Experimental) API
  slug: yuzu-health-eob-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-eob-experimental-api-openapi.yml
- filename: yuzu-health-group-policy-api-openapi.yml
  format: yaml
  label: Yuzu Health Group Policy API
  slug: yuzu-health-group-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-group-policy-api-openapi.yml
- filename: yuzu-health-member-api-openapi.yml
  format: yaml
  label: Yuzu Health Member API
  slug: yuzu-health-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-member-api-openapi.yml
- filename: yuzu-health-publicapiv1-api-openapi.yml
  format: yaml
  label: Yuzu Health PublicApiV1 API
  slug: yuzu-health-publicapiv1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-publicapiv1-api-openapi.yml
- filename: yuzu-health-publicapiv2-api-openapi.yml
  format: yaml
  label: Yuzu Health PublicApiV2 API
  slug: yuzu-health-publicapiv2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-publicapiv2-api-openapi.yml
- filename: yuzu-health-sponsor-api-openapi.yml
  format: yaml
  label: Yuzu Health Sponsor API
  slug: yuzu-health-sponsor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yuzu-health/openapi/yuzu-health-sponsor-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is operated in the United States and is not targeted to individuals in the European Economic Area or other countries outside the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial exploitation or competing product
    text: 8.1.15 use the Platform for any purpose other than that for which it is made available, to build or benchmark a competing product or service, or for any other commercial exploitation of the Platform or its content not expressly permitted by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the Platform, you must complete any required registration and provide information that is current, accurate, and complete
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yuzu Health
provenance_date: '2026-11-10'
provider_name: Yuzu Health
provider_slug: yuzu-health
slug: yuzu-health-eligibility
source_date: '2026-11-10'
source_filename: yuzu-health-eligibility.yml
source_heading: Eligibility
source_page: https://yuzu.health/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yuzu Health\naid: yuzu-health\nurl: https://yuzu.health/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is operated in the United States and is not targeted to individuals in the European Economic\n    Area or other countries outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial exploitation or competing product\n  text: 8.1.15 use the Platform for any purpose other than that for which it is made available, to build or benchmark\n    a competing product or service, or for any other commercial exploitation of\
  \ the Platform or its content not\n    expressly permitted by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the Platform, you must complete any required registration and provide information that is current,\n    accurate, and complete\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yuzu-health/eligibility/yuzu-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Yuzu Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Insurance
- Health Plans
- Benefits Administration
- Claims
- Enrollment
- Payers
- Self-Funded
---
