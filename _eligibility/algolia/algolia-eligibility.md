---
api_specs:
- filename: algolia-search-api-openapi.yml
  format: yaml
  label: Algolia Search API
  slug: algolia-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-search-api-openapi.yml
- filename: algolia-insights-api-openapi.yml
  format: yaml
  label: Algolia Insights API
  slug: algolia-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-insights-api-openapi.yml
- filename: algolia-recommend-api-openapi.yml
  format: yaml
  label: Algolia Recommend API
  slug: algolia-recommend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-recommend-api-openapi.yml
- filename: algolia-analytics-api-openapi.yml
  format: yaml
  label: Algolia Analytics API
  slug: algolia-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-analytics-api-openapi.yml
- filename: algolia-abtesting-v3-api-openapi.yml
  format: yaml
  label: Algolia A/B Testing API
  slug: algolia-a-b-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-abtesting-v3-api-openapi.yml
- filename: algolia-personalization-api-openapi.yml
  format: yaml
  label: Algolia Personalization API
  slug: algolia-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-personalization-api-openapi.yml
- filename: algolia-advanced-personalization-api-openapi.yml
  format: yaml
  label: Algolia Advanced Personalization API
  slug: algolia-advanced-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-advanced-personalization-api-openapi.yml
- filename: algolia-crawler-api-openapi.yml
  format: yaml
  label: Algolia Crawler API
  slug: algolia-crawler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-crawler-api-openapi.yml
- filename: algolia-ingestion-api-openapi.yml
  format: yaml
  label: Algolia Ingestion API
  slug: algolia-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-ingestion-api-openapi.yml
- filename: algolia-query-suggestions-api-openapi.yml
  format: yaml
  label: Algolia Query Suggestions API
  slug: algolia-query-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-query-suggestions-api-openapi.yml
- filename: algolia-composition-api-openapi.yml
  format: yaml
  label: Algolia Composition API
  slug: algolia-composition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-composition-api-openapi.yml
- filename: algolia-agent-studio-api-openapi.yml
  format: yaml
  label: Algolia Agent Studio API
  slug: algolia-agent-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-agent-studio-api-openapi.yml
- filename: algolia-monitoring-api-openapi.yml
  format: yaml
  label: Algolia Monitoring API
  slug: algolia-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-monitoring-api-openapi.yml
- filename: algolia-ab-testing-api-openapi.yml
  format: yaml
  label: Algolia Ab Testing API
  slug: algolia-ab-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algolia/openapi/algolia-ab-testing-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Subscriber shall not enable use of the Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
  entity_types:
  - text: If you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant that you have the right, authority and capacity to bind such entity
    type: business
  - text: if Subscriber is an agency of, or contractor to, the US Government, it receives only those rights with respect to such software as are granted to all other end users under license
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: any use or transfer of the Services, Algolia Software and Documentation must be permitted under these laws and regulations.
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
name: Algolia
provenance_date: '2026-11-09'
provider_name: Algolia
provider_slug: algolia
slug: algolia-eligibility
source_date: '2026-11-09'
source_filename: algolia-eligibility.yml
source_heading: Eligibility
source_page: https://www.algolia.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Algolia\naid: algolia\nurl: https://www.algolia.com/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Subscriber shall not enable use of the Services in a U.S.-embargoed country or in violation of any U.S.\n    export law or regulation.\nentity_types:\n- type: business\n  text: If you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant\n    that you have the right, authority and capacity to bind such entity\n- type: government\n  text: if Subscriber is an agency of, or contractor to, the US Government, it receives only those\
  \ rights with respect\n    to such software as are granted to all other end users under license\nrestricted_uses:\n- summary: Export restrictions\n  text: any use or transfer of the Services, Algolia Software and Documentation must be permitted under these laws\n    and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algolia/eligibility/algolia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Algolia's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Discovery
- Recommendations
- Personalization
- Analytics
- E-Commerce
---
