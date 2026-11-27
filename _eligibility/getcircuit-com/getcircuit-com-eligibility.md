---
api_specs:
- filename: getcircuit-com-couriers-api-openapi.yml
  format: yaml
  label: Circuit Couriers API
  slug: getcircuit-com-couriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-couriers-api-openapi.yml
- filename: getcircuit-com-depots-api-openapi.yml
  format: yaml
  label: Circuit Depots API
  slug: getcircuit-com-depots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-depots-api-openapi.yml
- filename: getcircuit-com-drivers-api-openapi.yml
  format: yaml
  label: Circuit Drivers API
  slug: getcircuit-com-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-drivers-api-openapi.yml
- filename: getcircuit-com-live-plans-api-openapi.yml
  format: yaml
  label: Circuit Live Plans API
  slug: getcircuit-com-live-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-live-plans-api-openapi.yml
- filename: getcircuit-com-live-stops-api-openapi.yml
  format: yaml
  label: Circuit Live Stops API
  slug: getcircuit-com-live-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-live-stops-api-openapi.yml
- filename: getcircuit-com-members-api-openapi.yml
  format: yaml
  label: Circuit Members API
  slug: getcircuit-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-members-api-openapi.yml
- filename: getcircuit-com-operations-api-openapi.yml
  format: yaml
  label: Circuit Operations API
  slug: getcircuit-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-operations-api-openapi.yml
- filename: getcircuit-com-orders-api-openapi.yml
  format: yaml
  label: Circuit Orders API
  slug: getcircuit-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-orders-api-openapi.yml
- filename: getcircuit-com-pickup-locations-api-openapi.yml
  format: yaml
  label: Circuit Pickup Locations API
  slug: getcircuit-com-pickup-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-pickup-locations-api-openapi.yml
- filename: getcircuit-com-plans-api-openapi.yml
  format: yaml
  label: Circuit Plans API
  slug: getcircuit-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-plans-api-openapi.yml
- filename: getcircuit-com-routes-api-openapi.yml
  format: yaml
  label: Circuit Routes API
  slug: getcircuit-com-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-routes-api-openapi.yml
- filename: getcircuit-com-stops-api-openapi.yml
  format: yaml
  label: Circuit Stops API
  slug: getcircuit-com-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-stops-api-openapi.yml
- filename: getcircuit-com-team-api-openapi.yml
  format: yaml
  label: Circuit Team API
  slug: getcircuit-com-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-team-api-openapi.yml
- filename: getcircuit-com-unassigned-stops-api-openapi.yml
  format: yaml
  label: Circuit Unassigned Stops API
  slug: getcircuit-com-unassigned-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getcircuit-com/openapi/getcircuit-com-unassigned-stops-api-openapi.yml
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
  - summary: Restricted SMS message categories
    text: 'Spoke Dispatch cannot be used to send SMS messages around the following categories: High-risk financial services, Third-party lead generation, Services/Debt collection or forgiveness, “Get rich quick” schemes, Illegal substances/articles, Prescription drugs, Gambling, or “S.H.A.F.T.”'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All customers signing up for Spoke Dispatch will be required to submit payment card details as part of the process to allow automatic payments once the free trial period finishes.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Circuit
provenance_date: '2026-11-09'
provider_name: Circuit
provider_slug: getcircuit-com
slug: getcircuit-com-eligibility
source_date: '2026-11-09'
source_filename: getcircuit-com-eligibility.yml
source_heading: Eligibility
source_page: https://spoke.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Circuit\naid: getcircuit-com\nurl: https://spoke.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted SMS message categories\n  text: 'Spoke Dispatch cannot be used to send SMS messages around the following categories: High-risk financial\n    services, Third-party lead generation, Services/Debt collection or forgiveness, “Get rich quick” schemes, Illegal\n    substances/articles, Prescription drugs, Gambling, or “S.H.A.F.T.”'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All customers\
  \ signing up for Spoke Dispatch will be required to submit payment card details as part of the\n    process to allow automatic payments once the free trial period finishes.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getcircuit-com/eligibility/getcircuit-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Circuit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Platform
---
