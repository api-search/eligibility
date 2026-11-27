---
api_specs:
- filename: dreamfactory-system-api-openapi.yml
  format: yaml
  label: DreamFactory System API
  slug: system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-system-api-openapi.yml
- filename: dreamfactory-admin-api-openapi.yml
  format: yaml
  label: DreamFactory Admin API
  slug: dreamfactory-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-admin-api-openapi.yml
- filename: dreamfactory-app-api-openapi.yml
  format: yaml
  label: DreamFactory App API
  slug: dreamfactory-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-app-api-openapi.yml
- filename: dreamfactory-cors-api-openapi.yml
  format: yaml
  label: DreamFactory CORS API
  slug: dreamfactory-cors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-cors-api-openapi.yml
- filename: dreamfactory-custom-api-openapi.yml
  format: yaml
  label: DreamFactory Custom API
  slug: dreamfactory-custom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-custom-api-openapi.yml
- filename: dreamfactory-environment-api-openapi.yml
  format: yaml
  label: DreamFactory Environment API
  slug: dreamfactory-environment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-environment-api-openapi.yml
- filename: dreamfactory-event-api-openapi.yml
  format: yaml
  label: DreamFactory Event API
  slug: dreamfactory-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-event-api-openapi.yml
- filename: dreamfactory-limit-api-openapi.yml
  format: yaml
  label: DreamFactory Limit API
  slug: dreamfactory-limit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-limit-api-openapi.yml
- filename: dreamfactory-lookup-api-openapi.yml
  format: yaml
  label: DreamFactory Lookup API
  slug: dreamfactory-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-lookup-api-openapi.yml
- filename: dreamfactory-package-api-openapi.yml
  format: yaml
  label: DreamFactory Package API
  slug: dreamfactory-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-package-api-openapi.yml
- filename: dreamfactory-role-api-openapi.yml
  format: yaml
  label: DreamFactory Role API
  slug: dreamfactory-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-role-api-openapi.yml
- filename: dreamfactory-scripttype-api-openapi.yml
  format: yaml
  label: DreamFactory ScriptType API
  slug: dreamfactory-scripttype-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-scripttype-api-openapi.yml
- filename: dreamfactory-servicetype-api-openapi.yml
  format: yaml
  label: DreamFactory ServiceType API
  slug: dreamfactory-servicetype-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-servicetype-api-openapi.yml
- filename: dreamfactory-user-api-openapi.yml
  format: yaml
  label: DreamFactory User API
  slug: dreamfactory-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-user-api-openapi.yml
- filename: dreamfactory-app-group-api-openapi.yml
  format: yaml
  label: DreamFactory App Group API
  slug: dreamfactory-app-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-app-group-api-openapi.yml
- filename: dreamfactory-email-template-api-openapi.yml
  format: yaml
  label: DreamFactory Email Template API
  slug: dreamfactory-email-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dreamfactory/openapi/dreamfactory-email-template-api-openapi.yml
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
  - summary: Access limited to customer employees and contractors
    text: Customer may permit the Product to be accessed only by Customer’s employees or contractors.
  - summary: No commercial use beyond the license
    text: Customer may not sublicense, sell, resell, transfer, assign, distribute, allow others to make any commercial use of, use on a timeshare or service bureau basis, or generate income from allowing others to use the Product.
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
name: DreamFactory
provenance_date: '2026-11-09'
provider_name: DreamFactory
provider_slug: dreamfactory
slug: dreamfactory-eligibility
source_date: '2026-11-09'
source_filename: dreamfactory-eligibility.yml
source_heading: Eligibility
source_page: https://www.dreamfactory.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DreamFactory\naid: dreamfactory\nurl: https://www.dreamfactory.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Access limited to customer employees and contractors\n  text: Customer may permit the Product to be accessed only by Customer’s employees or contractors.\n- summary: No commercial use beyond the license\n  text: Customer may not sublicense, sell, resell, transfer, assign, distribute, allow others to make any commercial\n    use of, use on a timeshare or service bureau basis, or generate income from allowing\
  \ others to use the Product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dreamfactory/eligibility/dreamfactory-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from DreamFactory's own page on 2026-11-09.
synthetic: false
tags:
- Automation
- Deployment
- Documentation
- Generation
- Security
---
