---
api_specs:
- filename: twittrapi-com-account-actions-api-openapi.yml
  format: yaml
  label: twittrapi-com Account actions API
  slug: twittrapi-com-account-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-account-actions-api-openapi.yml
- filename: twittrapi-com-account-api-openapi.yml
  format: yaml
  label: twittrapi-com Account API
  slug: twittrapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-account-api-openapi.yml
- filename: twittrapi-com-communities-api-openapi.yml
  format: yaml
  label: twittrapi-com Communities API
  slug: twittrapi-com-communities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-communities-api-openapi.yml
- filename: twittrapi-com-jobs-api-openapi.yml
  format: yaml
  label: twittrapi-com Jobs API
  slug: twittrapi-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-jobs-api-openapi.yml
- filename: twittrapi-com-lists-api-openapi.yml
  format: yaml
  label: twittrapi-com Lists API
  slug: twittrapi-com-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-lists-api-openapi.yml
- filename: twittrapi-com-misc-api-openapi.yml
  format: yaml
  label: twittrapi-com Misc API
  slug: twittrapi-com-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-misc-api-openapi.yml
- filename: twittrapi-com-search-api-openapi.yml
  format: yaml
  label: twittrapi-com Search API
  slug: twittrapi-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-search-api-openapi.yml
- filename: twittrapi-com-trends-api-openapi.yml
  format: yaml
  label: twittrapi-com Trends API
  slug: twittrapi-com-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-trends-api-openapi.yml
- filename: twittrapi-com-tweets-api-openapi.yml
  format: yaml
  label: twittrapi-com Tweets API
  slug: twittrapi-com-tweets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-tweets-api-openapi.yml
- filename: twittrapi-com-users-api-openapi.yml
  format: yaml
  label: twittrapi-com Users API
  slug: twittrapi-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must not be subject to EU, UN, US or other applicable sanctions and do not act on behalf of a sanctioned person.
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  - text: If you use the Service on behalf of a company or other organisation, you accept these Terms for it and confirm that you are authorised to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons
    text: that you are not subject to EU, UN, US or other applicable sanctions and do not act on behalf of a sanctioned person
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: for business customers after approval, with card payments with invoice and auto top-up
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: twittrapi-com
provenance_date: '2026-11-10'
provider_name: twittrapi-com
provider_slug: twittrapi-com
slug: twittrapi-com-eligibility
source_date: '2026-11-10'
source_filename: twittrapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.twittrapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: twittrapi-com\naid: twittrapi-com\nurl: https://www.twittrapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users must not be subject to EU, UN, US or other applicable sanctions and do not act on behalf of a sanctioned\n    person.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\n- type: business\n  text: If you use the Service on behalf of a company or other organisation, you accept these Terms for it and confirm\n    that you are authorised to do so.\nrestricted_uses:\n- summary: Sanctioned persons\n\
  \  text: that you are not subject to EU, UN, US or other applicable sanctions and do not act on behalf of a sanctioned\n    person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: for business customers after approval, with card payments with invoice and auto top-up\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/twittrapi-com/eligibility/twittrapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from twittrapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Twitter
- X
- Data API
- MCP
---
