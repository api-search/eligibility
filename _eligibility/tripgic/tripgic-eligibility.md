---
api_specs:
- filename: tripgic-activity-api-openapi.yml
  format: yaml
  label: Tripgic Activity API
  slug: tripgic-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-activity-api-openapi.yml
- filename: tripgic-esim-api-openapi.yml
  format: yaml
  label: Tripgic Esim API
  slug: tripgic-esim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-esim-api-openapi.yml
- filename: tripgic-flight-api-openapi.yml
  format: yaml
  label: Tripgic Flight API
  slug: tripgic-flight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-flight-api-openapi.yml
- filename: tripgic-hotel-api-openapi.yml
  format: yaml
  label: Tripgic Hotel API
  slug: tripgic-hotel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-hotel-api-openapi.yml
- filename: tripgic-service-tour-api-openapi.yml
  format: yaml
  label: Tripgic Service Tour API
  slug: tripgic-service-tour-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-service-tour-api-openapi.yml
- filename: tripgic-train-api-openapi.yml
  format: yaml
  label: Tripgic Train API
  slug: tripgic-train-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-train-api-openapi.yml
- filename: tripgic-transfer-api-openapi.yml
  format: yaml
  label: Tripgic Transfer API
  slug: tripgic-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-transfer-api-openapi.yml
- filename: tripgic-visa-api-openapi.yml
  format: yaml
  label: Tripgic Visa API
  slug: tripgic-visa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tripgic/openapi/tripgic-visa-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the API for any illegal or unauthorized purpose.
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
name: Tripgic
provenance_date: '2026-11-10'
provider_name: Tripgic
provider_slug: tripgic
slug: tripgic-eligibility
source_date: '2026-11-10'
source_filename: tripgic-eligibility.yml
source_heading: Eligibility
source_page: https://www.tripgic.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tripgic\naid: tripgic\nurl: https://www.tripgic.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to these terms.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the API for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tripgic/eligibility/tripgic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tripgic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Booking
- Aggregator
---
