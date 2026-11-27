---
api_specs:
- filename: konfetti-account-api-openapi.yml
  format: yaml
  label: konfetti Account API
  slug: konfetti-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konfetti/openapi/konfetti-account-api-openapi.yml
- filename: konfetti-auth-api-openapi.yml
  format: yaml
  label: konfetti Auth API
  slug: konfetti-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konfetti/openapi/konfetti-auth-api-openapi.yml
- filename: konfetti-catalog-api-openapi.yml
  format: yaml
  label: konfetti Catalog API
  slug: konfetti-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konfetti/openapi/konfetti-catalog-api-openapi.yml
- filename: konfetti-checkout-api-openapi.yml
  format: yaml
  label: konfetti Checkout API
  slug: konfetti-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konfetti/openapi/konfetti-checkout-api-openapi.yml
- filename: konfetti-requests-api-openapi.yml
  format: yaml
  label: konfetti Requests API
  slug: konfetti-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konfetti/openapi/konfetti-requests-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Das Angebot richtet sich ausschließlich an Unternehmen sowie an Verbraucher
    type: business
  - text: Verbraucher, die voll geschäftsfähig sind und als natürliche Person das 18. Lebensjahr vollendet haben müssen.
    type: individual
  minimum_age:
    text: als natürliche Person das 18. Lebensjahr vollendet haben müssen
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
name: konfetti
provenance_date: '2026-11-09'
provider_name: konfetti
provider_slug: konfetti
slug: konfetti-eligibility
source_date: '2026-11-09'
source_filename: konfetti-eligibility.yml
source_heading: Eligibility
source_page: https://gokonfetti.com/de-de/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: konfetti\naid: konfetti\nurl: https://gokonfetti.com/de-de/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Das Angebot richtet sich ausschließlich an Unternehmen sowie an Verbraucher\n- type: individual\n  text: Verbraucher, die voll geschäftsfähig sind und als natürliche Person das 18. Lebensjahr vollendet haben müssen.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: als natürliche Person das 18. Lebensjahr vollendet haben\
  \ müssen\n"
source_yaml_url: https://artifacts.apis.io/konfetti/eligibility/konfetti-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from konfetti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Experience
- Booking
- Event
- Workshops
- Ticketing
- Gift Cards
- Travel And Leisure
- Germany
- Commerce
---
