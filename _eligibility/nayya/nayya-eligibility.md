---
api_specs:
- filename: nayya-benefits-api-openapi.yml
  format: yaml
  label: Nayya Benefits API
  slug: nayya-benefits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-benefits-api-openapi.yml
- filename: nayya-carriers-api-openapi.yml
  format: yaml
  label: Nayya Carriers API
  slug: nayya-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-carriers-api-openapi.yml
- filename: nayya-connections-api-openapi.yml
  format: yaml
  label: Nayya Connections API
  slug: nayya-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-connections-api-openapi.yml
- filename: nayya-dependents-api-openapi.yml
  format: yaml
  label: Nayya Dependents API
  slug: nayya-dependents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-dependents-api-openapi.yml
- filename: nayya-employees-api-openapi.yml
  format: yaml
  label: Nayya Employees API
  slug: nayya-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-employees-api-openapi.yml
- filename: nayya-employers-api-openapi.yml
  format: yaml
  label: Nayya Employers API
  slug: nayya-employers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-employers-api-openapi.yml
- filename: nayya-enrollments-api-openapi.yml
  format: yaml
  label: Nayya Enrollments API
  slug: nayya-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-enrollments-api-openapi.yml
- filename: nayya-recommendations-api-openapi.yml
  format: yaml
  label: Nayya Recommendations API
  slug: nayya-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-recommendations-api-openapi.yml
- filename: nayya-rule-templates-api-openapi.yml
  format: yaml
  label: Nayya Rule Templates API
  slug: nayya-rule-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-rule-templates-api-openapi.yml
- filename: nayya-snapshots-api-openapi.yml
  format: yaml
  label: Nayya Snapshots API
  slug: nayya-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-snapshots-api-openapi.yml
- filename: nayya-token-api-openapi.yml
  format: yaml
  label: Nayya Token API
  slug: nayya-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Nayya provides the Nayya Properties for use only by persons located in the United States.
  minimum_age:
    text: you are of legal age to form a binding contract with Nayya
    value: null
  restricted_uses:
  - summary: Commercial use and sales
    text: (iv) involves commercial activities and/or sales
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
name: Nayya
provenance_date: '2026-11-10'
provider_name: Nayya
provider_slug: nayya
slug: nayya-eligibility
source_date: '2026-11-10'
source_filename: nayya-eligibility.yml
source_heading: Eligibility
source_page: https://legal.nayya.com/end-user-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nayya\naid: nayya\nurl: https://legal.nayya.com/end-user-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Nayya provides the Nayya Properties for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use and sales\n  text: (iv) involves commercial activities and/or sales\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with Nayya\n"
source_yaml_url: https://artifacts.apis.io/nayya/eligibility/nayya-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nayya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Benefits
- Insurance
- Insurtech
- Health
- Decision Support
- Human Resources
- Enrollment
- Recommendations
- Artificial Intelligence
---
