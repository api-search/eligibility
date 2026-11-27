---
api_specs:
- filename: leap-create-meters-api-openapi.yml
  format: yaml
  label: Leap create meters API
  slug: leap-create-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-create-meters-api-openapi.yml
- filename: leap-group-dispatches-api-openapi.yml
  format: yaml
  label: Leap Group Dispatches API
  slug: leap-group-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-group-dispatches-api-openapi.yml
- filename: leap-meter-details-api-openapi.yml
  format: yaml
  label: Leap Meter Details API
  slug: leap-meter-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-meter-details-api-openapi.yml
- filename: leap-meter-dispatches-api-openapi.yml
  format: yaml
  label: Leap Meter Dispatches API
  slug: leap-meter-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-meter-dispatches-api-openapi.yml
- filename: leap-meter-enrollment-api-openapi.yml
  format: yaml
  label: Leap meter enrollment API
  slug: leap-meter-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-meter-enrollment-api-openapi.yml
- filename: leap-nominations-api-openapi.yml
  format: yaml
  label: Leap Nominations API
  slug: leap-nominations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-nominations-api-openapi.yml
- filename: leap-performance-api-openapi.yml
  format: yaml
  label: Leap Performance API
  slug: leap-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-performance-api-openapi.yml
- filename: leap-provisional-assets-api-openapi.yml
  format: yaml
  label: Leap provisional assets API
  slug: leap-provisional-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-provisional-assets-api-openapi.yml
- filename: leap-revenue-api-openapi.yml
  format: yaml
  label: Leap Revenue API
  slug: leap-revenue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-revenue-api-openapi.yml
- filename: leap-webhooks-api-openapi.yml
  format: yaml
  label: Leap Webhooks API
  slug: leap-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-webhooks-api-openapi.yml
- filename: leap-interval-data-upload-api-openapi.yml
  format: yaml
  label: Leap Interval Data Upload API
  slug: leap-interval-data-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leap/openapi/leap-interval-data-upload-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Access where illegal
    text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Leap
provenance_date: '2026-11-09'
provider_name: Leap
provider_slug: leap
slug: leap-eligibility
source_date: '2026-11-09'
source_filename: leap-eligibility.yml
source_heading: Eligibility
source_page: https://www.leap.energy/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leap\naid: leap\nurl: https://www.leap.energy/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind\
  \ you to these Terms\nrestricted_uses:\n- summary: Access where illegal\n  text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/leap/eligibility/leap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Leap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Electricity
- Virtual Power Plant
- Demand Response
- Distributed Energy Resources
- Grid Services
- Energy Markets
- Battery Storage
- EV Charging
- Smart Buildings
- Metering
- Webhook
- Climate Tech
---
