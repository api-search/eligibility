---
api_specs:
- filename: respondology-comment-results-api-openapi.yml
  format: yaml
  label: Respondology Comment Results API
  slug: respondology-comment-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/respondology/openapi/respondology-comment-results-api-openapi.yml
- filename: respondology-comments-api-openapi.yml
  format: yaml
  label: Respondology Comments API
  slug: respondology-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/respondology/openapi/respondology-comments-api-openapi.yml
- filename: respondology-moderation-reasons-api-openapi.yml
  format: yaml
  label: Respondology Moderation Reasons API
  slug: respondology-moderation-reasons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/respondology/openapi/respondology-moderation-reasons-api-openapi.yml
- filename: respondology-post-results-api-openapi.yml
  format: yaml
  label: Respondology Post Results API
  slug: respondology-post-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/respondology/openapi/respondology-post-results-api-openapi.yml
- filename: respondology-posts-api-openapi.yml
  format: yaml
  label: Respondology Posts API
  slug: respondology-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/respondology/openapi/respondology-posts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for the lawful internal business purposes of Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk and mission-critical uses
    text: Customer shall not use the software, including any AI functionality, in connection with any high-risk activities or mission-critical applications where failure could result in significant harm to persons or property.
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
name: Respondology
provenance_date: '2026-11-10'
provider_name: Respondology
provider_slug: respondology
slug: respondology-eligibility
source_date: '2026-11-10'
source_filename: respondology-eligibility.yml
source_heading: Eligibility
source_page: https://respondology.com/software-as-a-service-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Respondology\naid: respondology\nurl: https://respondology.com/software-as-a-service-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: solely for the lawful internal business purposes of Customer\nrestricted_uses:\n- summary: High-risk and mission-critical uses\n  text: Customer shall not use the software, including any AI functionality, in connection with any high-risk activities\n    or mission-critical applications where failure could result in significant harm to persons or property.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/respondology/eligibility/respondology-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Respondology's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Content Moderation
- Social Media
- Comment Moderation
- Trust and Safety
- Artificial Intelligence
- Brand Protection
- Social Listening
- Webhook
- Marketing
---
