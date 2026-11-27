---
api_specs:
- filename: calculate-co-nz-calculators-api-openapi.yml
  format: yaml
  label: Calculate.co.nz Calculators API
  slug: calculate-co-nz-calculators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calculate-co-nz/openapi/calculate-co-nz-calculators-api-openapi.yml
- filename: calculate-co-nz-discovery-api-openapi.yml
  format: yaml
  label: Calculate.co.nz Discovery API
  slug: calculate-co-nz-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calculate-co-nz/openapi/calculate-co-nz-discovery-api-openapi.yml
- filename: calculate-co-nz-reference-data-api-openapi.yml
  format: yaml
  label: Calculate.co.nz Reference data API
  slug: calculate-co-nz-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calculate-co-nz/openapi/calculate-co-nz-reference-data-api-openapi.yml
- filename: calculate-co-nz-service-api-openapi.yml
  format: yaml
  label: Calculate.co.nz Service API
  slug: calculate-co-nz-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calculate-co-nz/openapi/calculate-co-nz-service-api-openapi.yml
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
  - summary: Acceptable use limits
    text: You may not, however, attempt to disrupt or overload the site, scrape or copy the content or source code at scale
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You do not need to enter personal details or create an account to use any tool
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Calculate.co.nz
provenance_date: '2026-11-09'
provider_name: Calculate.co.nz
provider_slug: calculate-co-nz
slug: calculate-co-nz-eligibility
source_date: '2026-11-09'
source_filename: calculate-co-nz-eligibility.yml
source_heading: Eligibility
source_page: https://www.calculate.co.nz/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calculate.co.nz\naid: calculate-co-nz\nurl: https://www.calculate.co.nz/terms.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use limits\n  text: You may not, however, attempt to disrupt or overload the site, scrape or copy the content or source code\n    at scale\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You do not need to enter personal details or create an account to use any tool\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calculate-co-nz/eligibility/calculate-co-nz-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Calculate.co.nz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Calculators
- New Zealand
- Free
- Education
---
