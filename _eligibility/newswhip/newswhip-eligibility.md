---
api_specs:
- filename: newswhip-articles-api-openapi.yml
  format: yaml
  label: NewsWhip Articles API
  slug: newswhip-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-articles-api-openapi.yml
- filename: newswhip-articlesbyhrefs-api-openapi.yml
  format: yaml
  label: NewsWhip ArticlesByHrefs API
  slug: newswhip-articlesbyhrefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-articlesbyhrefs-api-openapi.yml
- filename: newswhip-fbinfluencers-api-openapi.yml
  format: yaml
  label: NewsWhip FbInfluencers API
  slug: newswhip-fbinfluencers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-fbinfluencers-api-openapi.yml
- filename: newswhip-fbposts-api-openapi.yml
  format: yaml
  label: NewsWhip FbPosts API
  slug: newswhip-fbposts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-fbposts-api-openapi.yml
- filename: newswhip-local-api-openapi.yml
  format: yaml
  label: NewsWhip Local API
  slug: newswhip-local-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-local-api-openapi.yml
- filename: newswhip-publisher-api-openapi.yml
  format: yaml
  label: NewsWhip Publisher API
  slug: newswhip-publisher-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-publisher-api-openapi.yml
- filename: newswhip-region-api-openapi.yml
  format: yaml
  label: NewsWhip Region API
  slug: newswhip-region-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-region-api-openapi.yml
- filename: newswhip-search-api-openapi.yml
  format: yaml
  label: NewsWhip Search API
  slug: newswhip-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-search-api-openapi.yml
- filename: newswhip-stats-api-openapi.yml
  format: yaml
  label: NewsWhip Stats API
  slug: newswhip-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-stats-api-openapi.yml
- filename: newswhip-twitterinfluencers-api-openapi.yml
  format: yaml
  label: NewsWhip TwitterInfluencers API
  slug: newswhip-twitterinfluencers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newswhip/openapi/newswhip-twitterinfluencers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You shall not access or use the Services if you are located in any jurisdiction in which the provision of the Services or other components is prohibited under applicable laws or regulations
  entity_types:
  - text: If you are entering into these Terms on behalf of a company, organization or another legal entity (an “Entity”), you are agreeing to the Terms for that Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Government surveillance and law enforcement
    text: NewsWhip Services may not be used directly or indirectly as part of any surveillance, intelligence gathering, policing, or law enforcement processes.
  - summary: Facebook data limits
    text: 'Service Data derived from Facebook may not be sold or used for: unlawful, misleading, discriminatory, or fraudulent purposes'
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
name: NewsWhip
provenance_date: '2026-11-10'
provider_name: NewsWhip
provider_slug: newswhip
slug: newswhip-eligibility
source_date: '2026-11-10'
source_filename: newswhip-eligibility.yml
source_heading: Eligibility
source_page: https://www.newswhip.com/newswhip-terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NewsWhip\naid: newswhip\nurl: https://www.newswhip.com/newswhip-terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You shall not access or use the Services if you are located in any jurisdiction in which the provision of\n    the Services or other components is prohibited under applicable laws or regulations\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company, organization or another legal entity (an “Entity”),\n    you are agreeing to the Terms for that Entity\nrestricted_uses:\n- summary: Government surveillance and\
  \ law enforcement\n  text: NewsWhip Services may not be used directly or indirectly as part of any surveillance, intelligence gathering,\n    policing, or law enforcement processes.\n- summary: Facebook data limits\n  text: 'Service Data derived from Facebook may not be sold or used for: unlawful, misleading, discriminatory, or\n    fraudulent purposes'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/newswhip/eligibility/newswhip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from NewsWhip's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media Intelligence
- Social Media Analytics
- News
- Content Analytics
- Engagement Data
- Predictive Analytics
- Media Monitoring
---
