---
api_specs:
- filename: tickitto-authentication-api-openapi.yml
  format: yaml
  label: Tickitto Authentication API
  slug: tickitto-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-authentication-api-openapi.yml
- filename: tickitto-availability-api-openapi.yml
  format: yaml
  label: Tickitto Availability API
  slug: tickitto-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-availability-api-openapi.yml
- filename: tickitto-basket-api-openapi.yml
  format: yaml
  label: Tickitto Basket API
  slug: tickitto-basket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-basket-api-openapi.yml
- filename: tickitto-events-api-openapi.yml
  format: yaml
  label: Tickitto Events API
  slug: tickitto-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-events-api-openapi.yml
- filename: tickitto-metadata-api-openapi.yml
  format: yaml
  label: Tickitto Metadata API
  slug: tickitto-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-metadata-api-openapi.yml
- filename: tickitto-search-api-openapi.yml
  format: yaml
  label: Tickitto Search API
  slug: tickitto-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-search-api-openapi.yml
- filename: tickitto-system-status-api-openapi.yml
  format: yaml
  label: Tickitto System Status API
  slug: tickitto-system-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-system-status-api-openapi.yml
- filename: tickitto-webhooks-api-openapi.yml
  format: yaml
  label: Tickitto Webhooks API
  slug: tickitto-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickitto/openapi/tickitto-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: by the consumer ("Consumer") from Tikety
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration with Tikety or the creation of an account is not necessary to buy tickets to Events.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tickitto
provenance_date: '2026-11-10'
provider_name: Tickitto
provider_slug: tickitto
slug: tickitto-eligibility
source_date: '2026-11-10'
source_filename: tickitto-eligibility.yml
source_heading: Eligibility
source_page: https://www.tickitto.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tickitto\naid: tickitto\nurl: https://www.tickitto.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: by the consumer (\"Consumer\") from Tikety\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration with Tikety or the creation of an account is not necessary to buy tickets to Events.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tickitto/eligibility/tickitto-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Tickitto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ticketing
- Event
- Marketplace
- Travel & Experiences
- Entertainment
- Payments
- Commerce
---
