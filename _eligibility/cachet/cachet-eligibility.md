---
api_specs:
- filename: cachet-connect-api-openapi.yml
  format: yaml
  label: Cachet Connect API
  slug: cachet-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-connect-api-openapi.yml
- filename: cachet-gig-events-api-openapi.yml
  format: yaml
  label: Cachet Gig-Events API
  slug: cachet-gig-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-gig-events-api-openapi.yml
- filename: cachet-user-api-openapi.yml
  format: yaml
  label: Cachet User API
  slug: cachet-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-user-api-openapi.yml
- filename: cachet-vehicle-events-api-openapi.yml
  format: yaml
  label: Cachet Vehicle events API
  slug: cachet-vehicle-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-vehicle-events-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating a user account on the platform, the user confirms that all information and confirmations provided by him are true – he is a person with full legal capacity (at least 18 years old) or has all the rights and powers to order services on behalf of the user.
    type: individual
  minimum_age:
    text: he is a person with full legal capacity (at least 18 years old)
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The above statements are assumed to be true and Cachet.me does not verify their accuracy.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cachet
provenance_date: '2026-11-09'
provider_name: Cachet
provider_slug: cachet
slug: cachet-eligibility
source_date: '2026-11-09'
source_filename: cachet-eligibility.yml
source_heading: Eligibility
source_page: https://cachet.me/en/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cachet\naid: cachet\nurl: https://cachet.me/en/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By creating a user account on the platform, the user confirms that all information and confirmations provided\n    by him are true – he is a person with full legal capacity (at least 18 years old) or has all the rights and\n    powers to order services on behalf of the user.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The above statements are assumed to be true and Cachet.me\
  \ does not verify their accuracy.\nminimum_age:\n  value: '18'\n  text: he is a person with full legal capacity (at least 18 years old)\n"
source_yaml_url: https://artifacts.apis.io/cachet/eligibility/cachet-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Cachet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Mobility
- Gig Economy
- Car Sharing
- Embedded Insurance
- Event
---
