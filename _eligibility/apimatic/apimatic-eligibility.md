---
api_specs:
- filename: apimatic-docs-portal-api-openapi.yml
  format: yaml
  label: APIMatic Portals API
  slug: apimatic-portals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimatic/openapi/apimatic-docs-portal-api-openapi.yml
- filename: apimatic-sdk-api-openapi.yml
  format: yaml
  label: APIMatic SDK Generation API
  slug: apimatic-sdk-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimatic/openapi/apimatic-sdk-api-openapi.yml
- filename: apimatic-transformation-api-openapi.yml
  format: yaml
  label: APIMatic Transformation API
  slug: apimatic-transformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimatic/openapi/apimatic-transformation-api-openapi.yml
- filename: apimatic-validation-api-openapi.yml
  format: yaml
  label: APIMatic Validation API
  slug: apimatic-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimatic/openapi/apimatic-validation-api-openapi.yml
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
  - summary: Unlawful or malicious use
    text: use apimatic.io to do anything unlawful, misleading, malicious, or discriminatory;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Depending on your plan and usage, you must provide us with a valid credit card number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: APIMatic
provenance_date: '2026-11-09'
provider_name: APIMatic
provider_slug: apimatic
slug: apimatic-eligibility
source_date: '2026-11-09'
source_filename: apimatic-eligibility.yml
source_heading: Eligibility
source_page: https://www.apimatic.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIMatic\naid: apimatic\nurl: https://www.apimatic.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or malicious use\n  text: use apimatic.io to do anything unlawful, misleading, malicious, or discriminatory;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Depending on your plan and usage, you must provide us with a valid credit card number.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apimatic/eligibility/apimatic-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from APIMatic's own page on 2026-11-09.
synthetic: false
tags:
- API Transformation
- Code Generation
- Developer Experience
- Developer Tools
- Documentation
- SDK Generation
- OpenAPI
---
