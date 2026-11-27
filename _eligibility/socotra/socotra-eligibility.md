---
api_specs:
- filename: socotra-auth-api-openapi.yml
  format: yaml
  label: Socotra Auth API
  slug: socotra-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-auth-api-openapi.yml
- filename: socotra-auxdata-api-openapi.yml
  format: yaml
  label: Socotra Auxdata API
  slug: socotra-auxdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-auxdata-api-openapi.yml
- filename: socotra-billing-api-openapi.yml
  format: yaml
  label: Socotra Billing API
  slug: socotra-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-billing-api-openapi.yml
- filename: socotra-business-stats-api-openapi.yml
  format: yaml
  label: Socotra Business Stats API
  slug: socotra-business-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-business-stats-api-openapi.yml
- filename: socotra-claim-api-openapi.yml
  format: yaml
  label: Socotra Claim API
  slug: socotra-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-claim-api-openapi.yml
- filename: socotra-compliance-api-openapi.yml
  format: yaml
  label: Socotra Compliance API
  slug: socotra-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-compliance-api-openapi.yml
- filename: socotra-config-api-openapi.yml
  format: yaml
  label: Socotra Config API
  slug: socotra-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-config-api-openapi.yml
- filename: socotra-contact-api-openapi.yml
  format: yaml
  label: Socotra Contact API
  slug: socotra-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-contact-api-openapi.yml
- filename: socotra-document-api-openapi.yml
  format: yaml
  label: Socotra Document API
  slug: socotra-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-document-api-openapi.yml
- filename: socotra-event-api-openapi.yml
  format: yaml
  label: Socotra Event API
  slug: socotra-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-event-api-openapi.yml
- filename: socotra-migration-api-openapi.yml
  format: yaml
  label: Socotra Migration API
  slug: socotra-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-migration-api-openapi.yml
- filename: socotra-payment-execution-api-openapi.yml
  format: yaml
  label: Socotra Payment Execution API
  slug: socotra-payment-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-payment-execution-api-openapi.yml
- filename: socotra-plugin-api-openapi.yml
  format: yaml
  label: Socotra Plugin API
  slug: socotra-plugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-plugin-api-openapi.yml
- filename: socotra-policy-api-openapi.yml
  format: yaml
  label: Socotra Policy API
  slug: socotra-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-policy-api-openapi.yml
- filename: socotra-producers-api-openapi.yml
  format: yaml
  label: Socotra Producers API
  slug: socotra-producers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-producers-api-openapi.yml
- filename: socotra-resource-api-openapi.yml
  format: yaml
  label: Socotra Resource API
  slug: socotra-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-resource-api-openapi.yml
- filename: socotra-search-api-openapi.yml
  format: yaml
  label: Socotra Search API
  slug: socotra-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-search-api-openapi.yml
- filename: socotra-work-management-api-openapi.yml
  format: yaml
  label: Socotra Work Management API
  slug: socotra-work-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socotra/openapi/socotra-work-management-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual subscriber, customer, member, or user of at least 18 years of age
    type: individual
  - text: or a single company, organization, or entity
    type: business
  minimum_age:
    text: THE SOCOTRA SERVICES ARE NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: No competitors of Socotra
    text: Access the Socotra Services if you are a direct competitor of Socotra, except with Socotra’s prior written consent, or for any other competitive purposes
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
name: Socotra
provenance_date: '2026-11-10'
provider_name: Socotra
provider_slug: socotra
slug: socotra-eligibility
source_date: '2026-11-10'
source_filename: socotra-eligibility.yml
source_heading: Eligibility
source_page: https://www.socotra.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Socotra\naid: socotra\nurl: https://www.socotra.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual subscriber, customer, member, or user of at least 18 years of age\n- type: business\n  text: or a single company, organization, or entity\nrestricted_uses:\n- summary: No competitors of Socotra\n  text: Access the Socotra Services if you are a direct competitor of Socotra, except with Socotra’s prior written\n    consent, or for any other competitive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE SOCOTRA SERVICES ARE NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/socotra/eligibility/socotra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Socotra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Core Platform
- Policy Administration
- Billing
- Claims
- Underwriting
- MCP
- Invoicing
---
