---
api_specs:
- filename: vooma-carriers-api-openapi.yml
  format: yaml
  label: Vooma Carriers API
  slug: vooma-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-carriers-api-openapi.yml
- filename: vooma-contacts-api-openapi.yml
  format: yaml
  label: Vooma Contacts API
  slug: vooma-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-contacts-api-openapi.yml
- filename: vooma-customers-api-openapi.yml
  format: yaml
  label: Vooma Customers API
  slug: vooma-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-customers-api-openapi.yml
- filename: vooma-locations-api-openapi.yml
  format: yaml
  label: Vooma Locations API
  slug: vooma-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-locations-api-openapi.yml
- filename: vooma-movements-api-openapi.yml
  format: yaml
  label: Vooma Movements API
  slug: vooma-movements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-movements-api-openapi.yml
- filename: vooma-quotes-api-openapi.yml
  format: yaml
  label: Vooma Quotes API
  slug: vooma-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-quotes-api-openapi.yml
- filename: vooma-shipments-api-openapi.yml
  format: yaml
  label: Vooma Shipments API
  slug: vooma-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-shipments-api-openapi.yml
- filename: vooma-tracking-status-api-openapi.yml
  format: yaml
  label: Vooma Tracking Status API
  slug: vooma-tracking-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-tracking-status-api-openapi.yml
- filename: vooma-webhooks-api-openapi.yml
  format: yaml
  label: Vooma Webhooks API
  slug: vooma-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-webhooks-api-openapi.yml
- filename: vooma-api-api-openapi.yml
  format: yaml
  label: Vooma API
  slug: vooma-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you and the entity that you represent (“Subscriber”) is unconditionally consenting to be bound by and is becoming a party to this Agreement with Vooma and you represent and warrant that you have the authority to bind such entity to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in violation of law
    text: (b) Subscriber’s use ofthe Vooma Service in violation of any applicable laws, rules or regulations
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
name: Vooma
provenance_date: '2026-11-10'
provider_name: Vooma
provider_slug: vooma
slug: vooma-eligibility
source_date: '2026-11-10'
source_filename: vooma-eligibility.yml
source_heading: Eligibility
source_page: https://www.vooma.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vooma\naid: vooma\nurl: https://www.vooma.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you and the entity that you represent (“Subscriber”) is unconditionally consenting to be bound by and is\n    becoming a party to this Agreement with Vooma and you represent and warrant that you have the authority to bind\n    such entity to these terms.\nrestricted_uses:\n- summary: Use in violation of law\n  text: (b) Subscriber’s use ofthe Vooma Service in violation of any applicable laws, rules or regulations\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vooma/eligibility/vooma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Vooma's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Freight
- Logistics
- Transportation
- TMS
- Agents
- Freight Brokerage
---
