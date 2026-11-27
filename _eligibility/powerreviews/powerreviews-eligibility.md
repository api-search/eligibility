---
api_specs:
- filename: powerreviews-b2b-answer-api-openapi.yml
  format: yaml
  label: PowerReviews B2B Answer API
  slug: powerreviews-b2b-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-b2b-answer-api-openapi.yml
- filename: powerreviews-b2b-merchantresponse-api-openapi.yml
  format: yaml
  label: PowerReviews B2B MerchantResponse API
  slug: powerreviews-b2b-merchantresponse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-b2b-merchantresponse-api-openapi.yml
- filename: powerreviews-b2b-question-api-openapi.yml
  format: yaml
  label: PowerReviews B2B Question API
  slug: powerreviews-b2b-question-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-b2b-question-api-openapi.yml
- filename: powerreviews-b2b-write-a-review-api-openapi.yml
  format: yaml
  label: PowerReviews B2B Write a Review API
  slug: powerreviews-b2b-write-a-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-b2b-write-a-review-api-openapi.yml
- filename: powerreviews-configuration-api-openapi.yml
  format: yaml
  label: PowerReviews Configuration API
  slug: powerreviews-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-configuration-api-openapi.yml
- filename: powerreviews-q-a-api-openapi.yml
  format: yaml
  label: PowerReviews Q&A API
  slug: powerreviews-q-a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-q-a-api-openapi.yml
- filename: powerreviews-reviews-api-openapi.yml
  format: yaml
  label: PowerReviews Reviews API
  slug: powerreviews-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-reviews-api-openapi.yml
- filename: powerreviews-snippets-api-openapi.yml
  format: yaml
  label: PowerReviews Snippets API
  slug: powerreviews-snippets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/powerreviews/openapi/powerreviews-snippets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served: []
    text: 'no software from the Site may be downloaded, exported or re-exported: (a) into (or to a national or resident of) Cuba, North Korea, Iran, Syria or any other country to which the United States has embargoed goods'
  minimum_age:
    text: The Site and its services are not directed to, and not intended for the use of, children younger than 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: For any unlawful purpose or to solicit others to perform or participate in any unlawful acts
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PowerReviews
provenance_date: '2026-11-10'
provider_name: PowerReviews
provider_slug: powerreviews
slug: powerreviews-eligibility
source_date: '2026-11-10'
source_filename: powerreviews-eligibility.yml
source_heading: Eligibility
source_page: https://www.powerreviews.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PowerReviews\naid: powerreviews\nurl: https://www.powerreviews.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: 'no software from the Site may be downloaded, exported or re-exported: (a) into (or to a national or resident\n    of) Cuba, North Korea, Iran, Syria or any other country to which the United States has embargoed goods'\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: For any unlawful purpose or to solicit others to perform or participate in any unlawful acts\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and its services are not directed to, and not intended for the use of, children younger than 18\n    years old.\n"
source_yaml_url: https://artifacts.apis.io/powerreviews/eligibility/powerreviews-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PowerReviews's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- Ratings and Reviews
- User Generated Content
- Retail
- Marketing
- Syndication
- Questions and Answers
- Product Data
---
