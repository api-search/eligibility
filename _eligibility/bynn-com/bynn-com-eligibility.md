---
api_specs:
- filename: bynn-com-age-verification-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Age Verification API
  slug: bynn-com-age-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-age-verification-api-openapi.yml
- filename: bynn-com-aml-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Aml API
  slug: bynn-com-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-aml-api-openapi.yml
- filename: bynn-com-api-keys-api-openapi.yml
  format: yaml
  label: Bynn Intelligence API Keys API
  slug: bynn-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-api-keys-api-openapi.yml
- filename: bynn-com-autodoc-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Autodoc API
  slug: bynn-com-autodoc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-autodoc-api-openapi.yml
- filename: bynn-com-documents-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Documents API
  slug: bynn-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-documents-api-openapi.yml
- filename: bynn-com-dossiers-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Dossiers API
  slug: bynn-com-dossiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-dossiers-api-openapi.yml
- filename: bynn-com-face-collections-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Collections API
  slug: bynn-com-face-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-collections-api-openapi.yml
- filename: bynn-com-face-enrollment-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Enrollment API
  slug: bynn-com-face-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-enrollment-api-openapi.yml
- filename: bynn-com-face-search-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Face Search API
  slug: bynn-com-face-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-face-search-api-openapi.yml
- filename: bynn-com-moderation-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Moderation API
  slug: bynn-com-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-moderation-api-openapi.yml
- filename: bynn-com-nfc-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Nfc API
  slug: bynn-com-nfc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-nfc-api-openapi.yml
- filename: bynn-com-sessions-api-openapi.yml
  format: yaml
  label: Bynn Intelligence Sessions API
  slug: bynn-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bynn-com/openapi/bynn-com-sessions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered solely to companies, public bodies, organisations and other legal entities, and to individuals acting for purposes of their trade, business, craft or profession. They are not offered to consumers.
    type: business
  minimum_age:
    text: The individual who accepts the Agreement on behalf of the Customer represents and warrants that they are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Safety-critical control
    text: The Customer shall not use any Output or Service as the sole means of controlling a vehicle, aircraft, vessel, robot, machine, medical device, energy or utility network
  - summary: Military end use
    text: for any end use prohibited by export control law, including the development of weapons of mass destruction, or any military end use without the required authorisation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bynn may require a business email address, or other information about the Customer, before it opens an Account or a Plan.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bynn Intelligence
provenance_date: '2026-11-09'
provider_name: Bynn Intelligence
provider_slug: bynn-com
slug: bynn-com-eligibility
source_date: '2026-11-09'
source_filename: bynn-com-eligibility.yml
source_heading: Eligibility
source_page: https://bynn.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bynn Intelligence\naid: bynn-com\nurl: https://bynn.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered solely to companies, public bodies, organisations and other legal entities, and\n    to individuals acting for purposes of their trade, business, craft or profession. They are not offered to consumers.\nrestricted_uses:\n- summary: Safety-critical control\n  text: The Customer shall not use any Output or Service as the sole means of controlling a vehicle, aircraft, vessel,\n    robot, machine, medical\
  \ device, energy or utility network\n- summary: Military end use\n  text: for any end use prohibited by export control law, including the development of weapons of mass destruction,\n    or any military end use without the required authorisation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bynn may require a business email address, or other information about the Customer, before it opens an Account\n    or a Plan.\nminimum_age:\n  value: '18'\n  text: The individual who accepts the Agreement on behalf of the Customer represents and warrants that they are\n    at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bynn-com/eligibility/bynn-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bynn Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Frontier Research
- Identity Verification
- Digital Trust
---
