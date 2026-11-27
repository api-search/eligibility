---
api_specs:
- filename: bodyspec-api-status-api-openapi.yml
  format: yaml
  label: BodySpec API Status API
  slug: bodyspec-api-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-api-status-api-openapi.yml
- filename: bodyspec-appointments-api-openapi.yml
  format: yaml
  label: BodySpec Appointments API
  slug: bodyspec-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-appointments-api-openapi.yml
- filename: bodyspec-availability-api-openapi.yml
  format: yaml
  label: BodySpec Availability API
  slug: bodyspec-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-availability-api-openapi.yml
- filename: bodyspec-bodyspec-api-api-openapi.yml
  format: yaml
  label: BodySpec BodySpec API
  slug: bodyspec-bodyspec-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-bodyspec-api-api-openapi.yml
- filename: bodyspec-locations-api-openapi.yml
  format: yaml
  label: BodySpec Locations API
  slug: bodyspec-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-locations-api-openapi.yml
- filename: bodyspec-partner-appointments-api-openapi.yml
  format: yaml
  label: BodySpec Partner Appointments API
  slug: bodyspec-partner-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-appointments-api-openapi.yml
- filename: bodyspec-partner-intake-api-openapi.yml
  format: yaml
  label: BodySpec Partner Intake API
  slug: bodyspec-partner-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-intake-api-openapi.yml
- filename: bodyspec-partner-orders-api-openapi.yml
  format: yaml
  label: BodySpec Partner Orders API
  slug: bodyspec-partner-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-orders-api-openapi.yml
- filename: bodyspec-partner-results-api-openapi.yml
  format: yaml
  label: BodySpec Partner Results API
  slug: bodyspec-partner-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-results-api-openapi.yml
- filename: bodyspec-partner-users-api-openapi.yml
  format: yaml
  label: BodySpec Partner Users API
  slug: bodyspec-partner-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-users-api-openapi.yml
- filename: bodyspec-partner-webhooks-api-openapi.yml
  format: yaml
  label: BodySpec Partner Webhooks API
  slug: bodyspec-partner-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-partner-webhooks-api-openapi.yml
- filename: bodyspec-reservations-api-openapi.yml
  format: yaml
  label: BodySpec Reservations API
  slug: bodyspec-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-reservations-api-openapi.yml
- filename: bodyspec-results-api-openapi.yml
  format: yaml
  label: BodySpec Results API
  slug: bodyspec-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-results-api-openapi.yml
- filename: bodyspec-services-api-openapi.yml
  format: yaml
  label: BodySpec Services API
  slug: bodyspec-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-services-api-openapi.yml
- filename: bodyspec-users-api-openapi.yml
  format: yaml
  label: BodySpec Users API
  slug: bodyspec-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bodyspec/openapi/bodyspec-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: While we are licensed in the states where we currently maintain operations... there are certain jurisdictions in which we do not offer our Services because we do not have required licenses.
  minimum_age:
    text: if you contribute or otherwise provide your own Health Information, you must be eighteen (18) years of age or older to agree to these TOS
    value: 18 for Health Information; 13 for account-only use
  restricted_uses:
  - summary: Not for diagnostic use
    text: The Services are not intended to be used by the customer for any diagnostic purpose and are not a substitute for professional medical advice.
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
name: BodySpec
provenance_date: '2026-11-09'
provider_name: BodySpec
provider_slug: bodyspec
slug: bodyspec-eligibility
source_date: '2026-11-09'
source_filename: bodyspec-eligibility.yml
source_heading: Eligibility
source_page: https://www.bodyspec.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BodySpec\naid: bodyspec\nurl: https://www.bodyspec.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: While we are licensed in the states where we currently maintain operations... there are certain jurisdictions\n    in which we do not offer our Services because we do not have required licenses.\nentity_types: []\nrestricted_uses:\n- summary: Not for diagnostic use\n  text: The Services are not intended to be used by the customer for any diagnostic purpose and are not a substitute\n    for professional medical advice.\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: 18 for Health Information; 13 for account-only use\n  text: if you contribute or otherwise provide your own Health Information, you must be eighteen (18) years of age\n    or older to agree to these TOS\n"
source_yaml_url: https://artifacts.apis.io/bodyspec/eligibility/bodyspec-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BodySpec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Fitness
- Data
---
