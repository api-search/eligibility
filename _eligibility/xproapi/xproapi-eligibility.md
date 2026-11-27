---
api_specs:
- filename: xproapi-default-api-openapi.yml
  format: yaml
  label: Xproapi Default API
  slug: xproapi-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-default-api-openapi.yml
- filename: xproapi-follow-followings-api-openapi.yml
  format: yaml
  label: Xproapi Follow, Followings API
  slug: xproapi-follow-followings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-follow-followings-api-openapi.yml
- filename: xproapi-tweet-activity-api-openapi.yml
  format: yaml
  label: Xproapi Tweet Activity API
  slug: xproapi-tweet-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-tweet-activity-api-openapi.yml
- filename: xproapi-tweets-api-openapi.yml
  format: yaml
  label: Xproapi Tweets API
  slug: xproapi-tweets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-tweets-api-openapi.yml
- filename: xproapi-users-api-openapi.yml
  format: yaml
  label: Xproapi Users API
  slug: xproapi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-users-api-openapi.yml
- filename: xproapi-followers-api-openapi.yml
  format: yaml
  label: Xproapi Followers API
  slug: xproapi-followers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-followers-api-openapi.yml
- filename: xproapi-following-api-openapi.yml
  format: yaml
  label: Xproapi Following API
  slug: xproapi-following-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-following-api-openapi.yml
- filename: xproapi-mentions-api-openapi.yml
  format: yaml
  label: Xproapi Mentions API
  slug: xproapi-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-mentions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age or possess the legal authority in your jurisdiction to enter into this contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or possess the legal authority in your jurisdiction to enter into this contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Use the Service for any unlawful, harassing, defamatory, or abusive purpose.
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
name: Xproapi
provenance_date: '2026-11-10'
provider_name: Xproapi
provider_slug: xproapi
slug: xproapi-eligibility
source_date: '2026-11-10'
source_filename: xproapi-eligibility.yml
source_heading: Eligibility
source_page: https://xproapi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xproapi\naid: xproapi\nurl: https://xproapi.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or possess the legal authority in your jurisdiction to enter into this\n    contract.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Use the Service for any unlawful, harassing, defamatory, or abusive purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or possess the\
  \ legal authority in your jurisdiction to enter into this\n    contract.\n"
source_yaml_url: https://artifacts.apis.io/xproapi/eligibility/xproapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Xproapi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- X
- Social
- Monitoring
- Data
---
