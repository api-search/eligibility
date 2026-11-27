---
api_specs:
- filename: overview
  format: yaml
  label: SE Ranking Data API
  slug: data-api
  spec_type: Postman
  url: https://www.postman.com/serankingdev/se-ranking-developers/overview
- filename: overview
  format: yaml
  label: SE Ranking Project API
  slug: project-api
  spec_type: Postman
  url: https://www.postman.com/serankingdev/se-ranking-developers/overview
- filename: se-ranking-account-system-api-openapi.yml
  format: yaml
  label: SE Ranking Account & system API
  slug: se-ranking-account-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-account-system-api-openapi.yml
- filename: se-ranking-ai-search-api-openapi.yml
  format: yaml
  label: SE Ranking AI search API
  slug: se-ranking-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-ai-search-api-openapi.yml
- filename: se-ranking-backlinks-api-openapi.yml
  format: yaml
  label: SE Ranking Backlinks API
  slug: se-ranking-backlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-backlinks-api-openapi.yml
- filename: se-ranking-domain-analysis-api-openapi.yml
  format: yaml
  label: SE Ranking Domain Analysis API
  slug: se-ranking-domain-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-domain-analysis-api-openapi.yml
- filename: se-ranking-keyword-research-api-openapi.yml
  format: yaml
  label: SE Ranking Keyword Research API
  slug: se-ranking-keyword-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-keyword-research-api-openapi.yml
- filename: se-ranking-serp-results-classic-api-openapi.yml
  format: yaml
  label: SE Ranking SERP Results > classic API
  slug: se-ranking-serp-results-classic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-serp-results-classic-api-openapi.yml
- filename: se-ranking-website-audit-api-openapi.yml
  format: yaml
  label: SE Ranking Website Audit API
  slug: se-ranking-website-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/se-ranking/openapi/se-ranking-website-audit-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: represents and warrants that they are of legal age to enter into a binding agreement
    type: individual
  - text: if accepting on behalf of a corporation, governmental organization or other legal entity, that they have the right, power, and authority to enter into this Agreement on behalf of Customer
    type: business
  - text: if Customer is an agency of the US Government or any contractor therefore
    type: government
  minimum_age:
    text: represents and warrants that they are of legal age to enter into a binding agreement
    value: null
  restricted_uses:
  - summary: No sensitive or regulated data
    text: Customer shall not input sensitive personal data, regulated data, or confidential business information into SE Visible.
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
name: SE Ranking
provenance_date: '2026-11-10'
provider_name: SE Ranking
provider_slug: se-ranking
slug: se-ranking-eligibility
source_date: '2026-11-10'
source_filename: se-ranking-eligibility.yml
source_heading: Eligibility
source_page: https://seranking.com/legal/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SE Ranking\naid: se-ranking\nurl: https://seranking.com/legal/terms-of-service.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: represents and warrants that they are of legal age to enter into a binding agreement\n- type: business\n  text: if accepting on behalf of a corporation, governmental organization or other legal entity, that they have\n    the right, power, and authority to enter into this Agreement on behalf of Customer\n- type: government\n  text: if Customer is an agency of the US Government or any\
  \ contractor therefore\nrestricted_uses:\n- summary: No sensitive or regulated data\n  text: Customer shall not input sensitive personal data, regulated data, or confidential business information into\n    SE Visible.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: represents and warrants that they are of legal age to enter into a binding agreement\n"
source_yaml_url: https://artifacts.apis.io/se-ranking/eligibility/se-ranking-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SE Ranking's own page on 2026-11-10.
synthetic: false
tags:
- SEO
- Keyword Research
- Rank Tracking
- Backlinks
- Competitor Analysis
- Website Audit
- AI Search
- Geo
- Digital Marketing
- MCP
- AI Agents
- Agent Skills
---
