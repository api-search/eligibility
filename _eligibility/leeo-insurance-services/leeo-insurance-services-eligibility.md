---
api_specs:
- filename: leeo-insurance-services-aggregates-api-openapi.yml
  format: yaml
  label: LEEO Insurance Services Aggregates API
  slug: leeo-insurance-services-aggregates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leeo-insurance-services/openapi/leeo-insurance-services-aggregates-api-openapi.yml
- filename: leeo-insurance-services-drivers-api-openapi.yml
  format: yaml
  label: LEEO Insurance Services Drivers API
  slug: leeo-insurance-services-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leeo-insurance-services/openapi/leeo-insurance-services-drivers-api-openapi.yml
- filename: leeo-insurance-services-reports-api-openapi.yml
  format: yaml
  label: LEEO Insurance Services Reports API
  slug: leeo-insurance-services-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leeo-insurance-services/openapi/leeo-insurance-services-reports-api-openapi.yml
- filename: leeo-insurance-services-trips-api-openapi.yml
  format: yaml
  label: LEEO Insurance Services Trips API
  slug: leeo-insurance-services-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leeo-insurance-services/openapi/leeo-insurance-services-trips-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may describe products and services that are available only in certain jurisdictions (or only parts of them).
  minimum_age:
    text: The Services not intended for children under the age of eighteen (18).
    value: '18'
  restricted_uses:
  - summary: Political or commercial use
    text: use our Services for any political or commercial purpose, aside from the purchase of goods or services if offered for sale through the Services by LEEO
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services offered by LEEO is subject to final determination of underwriting qualifications and acceptance by the underwriting insurance company
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LEEO Insurance Services
provenance_date: '2026-11-09'
provider_name: LEEO Insurance Services
provider_slug: leeo-insurance-services
slug: leeo-insurance-services-eligibility
source_date: '2026-11-09'
source_filename: leeo-insurance-services-eligibility.yml
source_heading: Eligibility
source_page: https://leeoinsurance.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LEEO Insurance Services\naid: leeo-insurance-services\nurl: https://leeoinsurance.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services may describe products and services that are available only in certain jurisdictions (or only\n    parts of them).\nentity_types: []\nrestricted_uses:\n- summary: Political or commercial use\n  text: use our Services for any political or commercial purpose, aside from the purchase of goods or services if\n    offered for sale through the Services by LEEO\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Your eligibility for particular products and services offered by LEEO is subject to final determination\n    of underwriting qualifications and acceptance by the underwriting insurance company\nminimum_age:\n  value: '18'\n  text: The Services not intended for children under the age of eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/leeo-insurance-services/eligibility/leeo-insurance-services-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LEEO Insurance Services's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Commercial Auto Insurance
- Telematics
- Fleet Management
- Driving Behavior
- Risk Management
- Managing General Agent
- Mobile SDK
---
