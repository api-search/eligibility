---
api_specs:
- filename: char-gen-com-account-catalog-api-openapi.yml
  format: yaml
  label: CharGen Account & catalog API
  slug: char-gen-com-account-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-account-catalog-api-openapi.yml
- filename: char-gen-com-billing-api-openapi.yml
  format: yaml
  label: CharGen Billing API
  slug: char-gen-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-billing-api-openapi.yml
- filename: char-gen-com-entities-api-openapi.yml
  format: yaml
  label: CharGen Entities API
  slug: char-gen-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-entities-api-openapi.yml
- filename: char-gen-com-generations-api-openapi.yml
  format: yaml
  label: CharGen Generations API
  slug: char-gen-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-generations-api-openapi.yml
- filename: char-gen-com-ping-api-openapi.yml
  format: yaml
  label: CharGen Ping API
  slug: char-gen-com-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-ping-api-openapi.yml
- filename: char-gen-com-public-pricing-api-openapi.yml
  format: yaml
  label: CharGen Public pricing API
  slug: char-gen-com-public-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-public-pricing-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm that neither you nor any owner or controller of your organisation is subject to sanctions administered by the United Kingdom, the European Union, or the United States, and that you will not access or use the Service from, or for the benefit of any person in, a territory subject to a comprehensive embargo.
  entity_types:
  - text: 'The Service is open to developers of all kinds: companies, sole traders, and individuals.'
    type: business
  - text: 'The Service is open to developers of all kinds: companies, sole traders, and individuals.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and embargoed territories
    text: You confirm that neither you nor any owner or controller of your organisation is subject to sanctions administered by the United Kingdom, the European Union, or the United States
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
name: CharGen
provenance_date: '2026-11-09'
provider_name: CharGen
provider_slug: char-gen-com
slug: char-gen-com-eligibility
source_date: '2026-11-09'
source_filename: char-gen-com-eligibility.yml
source_heading: Eligibility
source_page: https://char-gen.com/developers/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CharGen\naid: char-gen-com\nurl: https://char-gen.com/developers/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm that neither you nor any owner or controller of your organisation is subject to sanctions administered\n    by the United Kingdom, the European Union, or the United States, and that you will not access or use the Service\n    from, or for the benefit of any person in, a territory subject to a comprehensive embargo.\nentity_types:\n- type: business\n  text: 'The Service is open to developers of all kinds: companies, sole traders, and individuals.'\n- type:\
  \ individual\n  text: 'The Service is open to developers of all kinds: companies, sole traders, and individuals.'\nrestricted_uses:\n- summary: Sanctions and embargoed territories\n  text: You confirm that neither you nor any owner or controller of your organisation is subject to sanctions administered\n    by the United Kingdom, the European Union, or the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/char-gen-com/eligibility/char-gen-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CharGen's own page on 2026-11-09.
synthetic: false
tags:
- AI Art
- RPG Tools
- Character Generation
- Map Generation
- Campaign Building
- Audio Generation
---
