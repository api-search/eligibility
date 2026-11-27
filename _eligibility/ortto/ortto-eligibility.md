---
api_specs:
- filename: ortto-accounts-api-openapi.yml
  format: yaml
  label: Ortto Accounts API
  slug: ortto-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-accounts-api-openapi.yml
- filename: ortto-activities-api-openapi.yml
  format: yaml
  label: Ortto Activities API
  slug: ortto-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-activities-api-openapi.yml
- filename: ortto-campaigns-api-openapi.yml
  format: yaml
  label: Ortto Campaigns API
  slug: ortto-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-campaigns-api-openapi.yml
- filename: ortto-people-api-openapi.yml
  format: yaml
  label: Ortto People API
  slug: ortto-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-people-api-openapi.yml
- filename: ortto-tags-api-openapi.yml
  format: yaml
  label: Ortto Tags API
  slug: ortto-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-tags-api-openapi.yml
- filename: ortto-transactional-api-openapi.yml
  format: yaml
  label: Ortto Transactional API
  slug: ortto-transactional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ortto/openapi/ortto-transactional-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Service may not be exported or re-exported into any U.S. embargoed countries or to anyone on the U.S. Treasury Department's list of Specially Designated Nationals
  entity_types:
  - text: To use and/or register for the Service, you agree that you must be of legal age to form a binding contract with Ortto.
    type: individual
  - text: If you use the Service on behalf of an entity, you represent and warrant to Ortto that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you must be of legal age to form a binding contract with Ortto
    value: null
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
name: Ortto
provenance_date: '2026-11-10'
provider_name: Ortto
provider_slug: ortto
slug: ortto-eligibility
source_date: '2026-11-10'
source_filename: ortto-eligibility.yml
source_heading: Eligibility
source_page: https://ortto.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ortto\naid: ortto\nurl: https://ortto.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Service may not be exported or re-exported into any U.S. embargoed countries or to anyone on the U.S. Treasury\n    Department's list of Specially Designated Nationals\nentity_types:\n- type: individual\n  text: To use and/or register for the Service, you agree that you must be of legal age to form a binding contract\n    with Ortto.\n- type: business\n  text: If you use the Service on behalf of an entity, you represent and warrant to Ortto that you have the authority\n    to bind that\
  \ entity to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you must be of legal age to form a binding contract with Ortto\n"
source_yaml_url: https://artifacts.apis.io/ortto/eligibility/ortto-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Ortto's own page on 2026-11-10.
synthetic: false
tags:
- Marketing Automation
- CDP
- Customer Data Platform
- Analytics
- Email
- SMS
- Transactional Email
- Webhook
- MCP
- Push Notifications
---
