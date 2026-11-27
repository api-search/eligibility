---
api_specs:
- filename: noerrands-com-booking-api-openapi.yml
  format: yaml
  label: noerrands-com Booking API
  slug: noerrands-com-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-booking-api-openapi.yml
- filename: noerrands-com-cards-api-openapi.yml
  format: yaml
  label: noerrands-com Cards API
  slug: noerrands-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-cards-api-openapi.yml
- filename: noerrands-com-fax-api-openapi.yml
  format: yaml
  label: noerrands-com Fax API
  slug: noerrands-com-fax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-fax-api-openapi.yml
- filename: noerrands-com-mail-api-openapi.yml
  format: yaml
  label: noerrands-com Mail API
  slug: noerrands-com-mail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-mail-api-openapi.yml
- filename: noerrands-com-prints-api-openapi.yml
  format: yaml
  label: noerrands-com Prints API
  slug: noerrands-com-prints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-prints-api-openapi.yml
- filename: noerrands-com-ship-api-openapi.yml
  format: yaml
  label: noerrands-com Ship API
  slug: noerrands-com-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-ship-api-openapi.yml
- filename: noerrands-com-sign-api-openapi.yml
  format: yaml
  label: noerrands-com Sign API
  slug: noerrands-com-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-sign-api-openapi.yml
- filename: noerrands-com-tables-api-openapi.yml
  format: yaml
  label: noerrands-com Tables API
  slug: noerrands-com-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-tables-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The service is offered in the United States only.
  entity_types:
  - text: You must be 18 or older and able to enter a contract.
    type: individual
  - text: If you use it for an organisation, you confirm you are allowed to bind that organisation.
    type: business
  minimum_age:
    text: You must be 18 or older and able to enter a contract.
    value: '18'
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
name: noerrands-com
provenance_date: '2026-11-10'
provider_name: noerrands-com
provider_slug: noerrands-com
slug: noerrands-com-eligibility
source_date: '2026-11-10'
source_filename: noerrands-com-eligibility.yml
source_heading: Eligibility
source_page: https://noerrands.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: noerrands-com\naid: noerrands-com\nurl: https://noerrands.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The service is offered in the United States only.\nentity_types:\n- type: individual\n  text: You must be 18 or older and able to enter a contract.\n- type: business\n  text: If you use it for an organisation, you confirm you are allowed to bind that organisation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/noerrands-com/eligibility/noerrands-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from noerrands-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Productivity
- Messaging
---
