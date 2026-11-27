---
api_specs:
- filename: mention-accounts-api-openapi.yml
  format: yaml
  label: Mention Accounts API
  slug: mention-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-accounts-api-openapi.yml
- filename: mention-alerts-api-openapi.yml
  format: yaml
  label: Mention Alerts API
  slug: mention-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-alerts-api-openapi.yml
- filename: mention-authors-api-openapi.yml
  format: yaml
  label: Mention Authors API
  slug: mention-authors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-authors-api-openapi.yml
- filename: mention-mentions-api-openapi.yml
  format: yaml
  label: Mention Mentions API
  slug: mention-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-mentions-api-openapi.yml
- filename: mention-shares-api-openapi.yml
  format: yaml
  label: Mention Shares API
  slug: mention-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-shares-api-openapi.yml
- filename: mention-stats-api-openapi.yml
  format: yaml
  label: Mention Stats API
  slug: mention-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-stats-api-openapi.yml
- filename: mention-tags-api-openapi.yml
  format: yaml
  label: Mention Tags API
  slug: mention-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-tags-api-openapi.yml
- filename: mention-tasks-api-openapi.yml
  format: yaml
  label: Mention Tasks API
  slug: mention-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-tasks-api-openapi.yml
- filename: mention-app-api-openapi.yml
  format: yaml
  label: Mention App API
  slug: mention-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mention/openapi/mention-app-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended exclusively for professionals, this being understood as referring to any natural or artificial persons performing a non-occasional paid activity in all branches of industry and business.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business purposes only
    text: The Client must only use Services for internal business purposes
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
name: Mention
provenance_date: '2026-11-10'
provider_name: Mention
provider_slug: mention
slug: mention-eligibility
source_date: '2026-11-10'
source_filename: mention-eligibility.yml
source_heading: Eligibility
source_page: https://mention.com/en/terms-and-conditions/#general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mention\naid: mention\nurl: https://mention.com/en/terms-and-conditions/#general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended exclusively for professionals, this being understood as referring to any natural\n    or artificial persons performing a non-occasional paid activity in all branches of industry and business.\nrestricted_uses:\n- summary: Internal business purposes only\n  text: The Client must only use Services for internal business purposes\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mention/eligibility/mention-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Mention's own page on 2026-11-10.
synthetic: false
tags:
- Alerts
- Brand Monitoring
- Media Monitoring
- Social Listening
- Social Media
- Sentiment Analysis
- Reputation Management
- Influencer Marketing
- Competitive Intelligence
- Streaming
- Marketing
---
