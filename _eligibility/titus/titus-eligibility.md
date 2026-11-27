---
api_specs:
- filename: titus-authorizations-api-openapi.yml
  format: yaml
  label: Titus Authorizations API
  slug: titus-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-authorizations-api-openapi.yml
- filename: titus-businessconnections-api-openapi.yml
  format: yaml
  label: Titus Business Connections API
  slug: titus-businessconnections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-businessconnections-api-openapi.yml
- filename: titus-checkouts-api-openapi.yml
  format: yaml
  label: Titus Checkouts API
  slug: titus-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-checkouts-api-openapi.yml
- filename: titus-customers-api-openapi.yml
  format: yaml
  label: Titus Customers API
  slug: titus-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-customers-api-openapi.yml
- filename: titus-listings-api-openapi.yml
  format: yaml
  label: Titus Listings API
  slug: titus-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-listings-api-openapi.yml
- filename: titus-platformpayouts-api-openapi.yml
  format: yaml
  label: Titus Platform Payouts API
  slug: titus-platformpayouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-platformpayouts-api-openapi.yml
- filename: titus-refunds-api-openapi.yml
  format: yaml
  label: Titus Refunds API
  slug: titus-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-refunds-api-openapi.yml
- filename: titus-titus-api-api-openapi.yml
  format: yaml
  label: Titus Titus API
  slug: titus-titus-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/titus/openapi/titus-titus-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent and warrant that you: (a) are of legal age to form a binding contract'
    type: individual
  minimum_age:
    text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 18
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries and parties
    text: 'you are not: (a) located in a country that is subject to a U.S. Government embargo'
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
name: Titus
provenance_date: '2026-11-10'
provider_name: Titus
provider_slug: titus
slug: titus-eligibility
source_date: '2026-11-10'
source_filename: titus-eligibility.yml
source_heading: Eligibility
source_page: https://www.gotitus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Titus\naid: titus\nurl: https://www.gotitus.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You represent and warrant that you: (a) are of legal age to form a binding contract'\nrestricted_uses:\n- summary: Sanctioned countries and parties\n  text: 'you are not: (a) located in a country that is subject to a U.S. Government embargo'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 18\n"
source_yaml_url: https://artifacts.apis.io/titus/eligibility/titus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Titus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Orchestration
- B2B
---
