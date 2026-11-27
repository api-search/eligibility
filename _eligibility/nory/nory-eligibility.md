---
api_specs:
- filename: nory-authorization-api-openapi.yml
  format: yaml
  label: Nory Authorization API
  slug: nory-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-authorization-api-openapi.yml
- filename: nory-branch-api-openapi.yml
  format: yaml
  label: Nory Branch API
  slug: nory-branch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-branch-api-openapi.yml
- filename: nory-brands-api-openapi.yml
  format: yaml
  label: Nory Brands API
  slug: nory-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-brands-api-openapi.yml
- filename: nory-employee-punch-api-openapi.yml
  format: yaml
  label: Nory Employee Punch API
  slug: nory-employee-punch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-employee-punch-api-openapi.yml
- filename: nory-integration-api-openapi.yml
  format: yaml
  label: Nory Integration API
  slug: nory-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-integration-api-openapi.yml
- filename: nory-inventory-api-openapi.yml
  format: yaml
  label: Nory Inventory API
  slug: nory-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-inventory-api-openapi.yml
- filename: nory-inventory-orders-api-openapi.yml
  format: yaml
  label: Nory Inventory Orders API
  slug: nory-inventory-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-inventory-orders-api-openapi.yml
- filename: nory-location-settings-api-openapi.yml
  format: yaml
  label: Nory Location Settings API
  slug: nory-location-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-location-settings-api-openapi.yml
- filename: nory-refresh-token-api-openapi.yml
  format: yaml
  label: Nory Refresh token API
  slug: nory-refresh-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-refresh-token-api-openapi.yml
- filename: nory-templates-api-openapi.yml
  format: yaml
  label: Nory Templates API
  slug: nory-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Terms distinguish EU Customers and U.S. Customers, and state that if Customer's billing address is in the United States, additional U.S.-specific terms apply.
  entity_types:
  - text: the entity or person that purchases the services (the "Customer")
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed or sanctioned use
    text: The Customer will not permit access to or use of the Services in embargoed jurisdictions or by prohibited parties.
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
name: Nory
provenance_date: '2026-11-10'
provider_name: Nory
provider_slug: nory
slug: nory-eligibility
source_date: '2026-11-10'
source_filename: nory-eligibility.yml
source_heading: Eligibility
source_page: https://www.nory.ai/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nory\naid: nory\nurl: https://www.nory.ai/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Terms distinguish EU Customers and U.S. Customers, and state that if Customer's billing address is in\n    the United States, additional U.S.-specific terms apply.\nentity_types:\n- type: other\n  text: the entity or person that purchases the services (the \"Customer\")\nrestricted_uses:\n- summary: Embargoed or sanctioned use\n  text: The Customer will not permit access to or use of the Services in embargoed jurisdictions or by prohibited\n\
  \    parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nory/eligibility/nory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Nory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Hospitality
- Inventory
- Workforce
- Payroll
- Point-of-Sale
- Artificial Intelligence
- Food and Beverage
---
