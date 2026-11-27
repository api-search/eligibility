---
api_specs:
- filename: nhs-api-codesystem-api-openapi.yml
  format: yaml
  label: NHS API CodeSystem API
  slug: nhs-api-codesystem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-codesystem-api-openapi.yml
- filename: nhs-api-list-id-api-openapi.yml
  format: yaml
  label: NHS API List{id} API
  slug: nhs-api-list-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-list-id-api-openapi.yml
- filename: nhs-api-metadata-api-openapi.yml
  format: yaml
  label: NHS API Metadata API
  slug: nhs-api-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-metadata-api-openapi.yml
- filename: nhs-api-organization-api-openapi.yml
  format: yaml
  label: NHS API Organization API
  slug: nhs-api-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-organization-api-openapi.yml
- filename: nhs-api-organizationaffiliation-api-openapi.yml
  format: yaml
  label: NHS API OrganizationAffiliation API
  slug: nhs-api-organizationaffiliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-organizationaffiliation-api-openapi.yml
- filename: nhs-api-r4-api-openapi.yml
  format: yaml
  label: NHS API R4 API
  slug: nhs-api-r4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-r4-api-openapi.yml
- filename: nhs-api-stu3-api-openapi.yml
  format: yaml
  label: NHS API STU3 API
  slug: nhs-api-stu3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-stu3-api-openapi.yml
- filename: nhs-api-valueset-api-openapi.yml
  format: yaml
  label: NHS API ValueSet API
  slug: nhs-api-valueset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nhs-api/openapi/nhs-api-valueset-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The API Service is intended for use in association with products to be used in England.
  entity_types:
  - text: These terms of use apply to your personal use of the API Service.
    type: individual
  - text: Your organisation is subject to the terms of its Connection Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: use it in any unlawful manner, for any unlawful purpose
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
name: NHS API
provenance_date: '2026-11-10'
provider_name: NHS API
provider_slug: nhs-api
slug: nhs-api-eligibility
source_date: '2026-11-10'
source_filename: nhs-api-eligibility.yml
source_heading: Eligibility
source_page: https://onboarding.prod.api.platform.nhs.uk/PolicyPages/TermsOfUsePolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NHS API\naid: nhs-api\nurl: https://onboarding.prod.api.platform.nhs.uk/PolicyPages/TermsOfUsePolicy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The API Service is intended for use in association with products to be used in England.\nentity_types:\n- type: individual\n  text: These terms of use apply to your personal use of the API Service.\n- type: business\n  text: Your organisation is subject to the terms of its Connection Agreement.\nrestricted_uses:\n- summary: Unlawful use\n  text: use it in any unlawful manner, for any unlawful purpose\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nhs-api/eligibility/nhs-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from NHS API's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- FHIR
- NHS
- United Kingdom
- HL7
- Electronic Prescriptions
- Patient Demographics
- GP Connect
- NHS Login
- Interoperability
---
