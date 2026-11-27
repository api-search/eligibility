---
api_specs:
- filename: openweb-export-api-openapi.yml
  format: yaml
  label: OpenWeb Export API
  slug: openweb-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-export-api-openapi.yml
- filename: openweb-top-comments-api-openapi.yml
  format: yaml
  label: OpenWeb top comments API
  slug: openweb-top-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-top-comments-api-openapi.yml
- filename: openweb-trending-articles-api-openapi.yml
  format: yaml
  label: OpenWeb trending articles API
  slug: openweb-trending-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-trending-articles-api-openapi.yml
- filename: openweb-article-api-openapi.yml
  format: yaml
  label: OpenWeb Article API
  slug: openweb-article-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-article-api-openapi.yml
- filename: openweb-comment-api-openapi.yml
  format: yaml
  label: OpenWeb Comment API
  slug: openweb-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-comment-api-openapi.yml
- filename: openweb-live-blog-api-openapi.yml
  format: yaml
  label: OpenWeb live blog API
  slug: openweb-live-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-live-blog-api-openapi.yml
- filename: openweb-moderation-policy-api-openapi.yml
  format: yaml
  label: OpenWeb moderation policy API
  slug: openweb-moderation-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-moderation-policy-api-openapi.yml
- filename: openweb-score-and-reviews-api-openapi.yml
  format: yaml
  label: OpenWeb score and reviews API
  slug: openweb-score-and-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-score-and-reviews-api-openapi.yml
- filename: openweb-sso-api-openapi.yml
  format: yaml
  label: OpenWeb SSO API
  slug: openweb-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-sso-api-openapi.yml
- filename: openweb-token-api-openapi.yml
  format: yaml
  label: OpenWeb Token API
  slug: openweb-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openweb/openapi/openweb-token-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Publisher ” means the entity identified in the Services Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: Neither Company nor Publisher shall encourage the posting of any User Content which may contain adult, obscene, pornographic, defamatory, libelous, infringing, abusive, or illegal content
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
name: OpenWeb
provenance_date: '2026-11-10'
provider_name: OpenWeb
provider_slug: openweb
slug: openweb-eligibility
source_date: '2026-11-10'
source_filename: openweb-eligibility.yml
source_heading: Eligibility
source_page: https://www.openweb.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenWeb\naid: openweb\nurl: https://www.openweb.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Publisher ” means the entity identified in the Services Agreement.\nrestricted_uses:\n- summary: Prohibited content\n  text: Neither Company nor Publisher shall encourage the posting of any User Content which may contain adult, obscene,\n    pornographic, defamatory, libelous, infringing, abusive, or illegal content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openweb/eligibility/openweb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from OpenWeb's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Community
- Comments
- Audience Engagement
- Publishing
- Media
- Moderation
- Identity
- SSO
- Webhook
---
