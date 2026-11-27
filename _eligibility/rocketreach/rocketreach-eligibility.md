---
api_specs:
- filename: rocketreach-account-api-openapi.yml
  format: yaml
  label: RocketReach Account API
  slug: rocketreach-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketreach/openapi/rocketreach-account-api-openapi.yml
- filename: rocketreach-company-data-api-api-openapi.yml
  format: yaml
  label: RocketReach Company Data API
  slug: rocketreach-company-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketreach/openapi/rocketreach-company-data-api-api-openapi.yml
- filename: rocketreach-people-data-api-api-openapi.yml
  format: yaml
  label: RocketReach People Data API
  slug: rocketreach-people-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocketreach/openapi/rocketreach-people-data-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'The Services are offered by RocketReach, LLC located at 144 N 7th St, PO #421, Brooklyn, NY 11211.'
  entity_types:
  - text: The Services and Lookup Information are available only to individuals who are at least 18 years old.
    type: individual
  - text: If you are using the Services on behalf of a company, you grant (and you represent and warrant that you have the authority to grant) RocketReach
    type: business
  minimum_age:
    text: The Services and Lookup Information are available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or third-party-breaching use
    text: you agree not to use the Services or any product of the Services, including Lookup Information, for any unlawful purpose or in contravention of any applicable laws or regulations.
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
name: RocketReach
provenance_date: '2026-11-10'
provider_name: RocketReach
provider_slug: rocketreach
slug: rocketreach-eligibility
source_date: '2026-11-10'
source_filename: rocketreach-eligibility.yml
source_heading: Eligibility
source_page: https://rocketreach.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RocketReach\naid: rocketreach\nurl: https://rocketreach.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'The Services are offered by RocketReach, LLC located at 144 N 7th St, PO #421, Brooklyn, NY 11211.'\nentity_types:\n- type: individual\n  text: The Services and Lookup Information are available only to individuals who are at least 18 years old.\n- type: business\n  text: If you are using the Services on behalf of a company, you grant (and you represent and warrant that you\n    have the authority to grant) RocketReach\nrestricted_uses:\n- summary: Unlawful or third-party-breaching\
  \ use\n  text: you agree not to use the Services or any product of the Services, including Lookup Information, for any\n    unlawful purpose or in contravention of any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services and Lookup Information are available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/rocketreach/eligibility/rocketreach-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from RocketReach's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Contact Data
- Email Lookup
- Phone Lookup
- Sales Intelligence
- Lead Generation
- People Search
- Company Search
- Data Enrichment
- Prospecting
- Recruiting
- Webhook
---
