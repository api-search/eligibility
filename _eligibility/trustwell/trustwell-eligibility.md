---
api_specs:
- filename: trustwell-compliance-api-openapi.yml
  format: yaml
  label: Trustwell Compliance API
  slug: trustwell-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-compliance-api-openapi.yml
- filename: trustwell-products-api-openapi.yml
  format: yaml
  label: Trustwell Products API
  slug: trustwell-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-products-api-openapi.yml
- filename: trustwell-quality-api-openapi.yml
  format: yaml
  label: Trustwell Quality API
  slug: trustwell-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-quality-api-openapi.yml
- filename: trustwell-recalls-api-openapi.yml
  format: yaml
  label: Trustwell Recalls API
  slug: trustwell-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-recalls-api-openapi.yml
- filename: trustwell-suppliers-api-openapi.yml
  format: yaml
  label: Trustwell Suppliers API
  slug: trustwell-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-suppliers-api-openapi.yml
- filename: trustwell-traceability-api-openapi.yml
  format: yaml
  label: Trustwell Traceability API
  slug: trustwell-traceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-traceability-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Licensee may use the Licensed Software solely for its internal business use by its own employees, consultants, advisors or agents in the manner licensed in this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No life-critical use
    text: (j) use the Licensed Software or its hosting server(s) for any use in which the failure of the Licensed Software or its hosting server(s) could lead to the death or serious bodily injury of any person, or to severe physical or environmental damage.
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
name: Trustwell
provenance_date: '2026-11-10'
provider_name: Trustwell
provider_slug: trustwell
slug: trustwell-eligibility
source_date: '2026-11-10'
source_filename: trustwell-eligibility.yml
source_heading: Eligibility
source_page: https://www.trustwell.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trustwell\naid: trustwell\nurl: https://www.trustwell.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Licensee may use the Licensed Software solely for its internal business use by its own employees, consultants,\n    advisors or agents in the manner licensed in this Agreement.\nrestricted_uses:\n- summary: No life-critical use\n  text: (j) use the Licensed Software or its hosting server(s) for any use in which the failure of the Licensed\n    Software or its hosting server(s) could lead to the death or serious\
  \ bodily injury of any person, or to severe\n    physical or environmental damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trustwell/eligibility/trustwell-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Trustwell's own page on 2026-11-10.
synthetic: false
tags:
- FoodIndustry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology
- Quality Management
- Recall
- Artificial Intelligence
---
