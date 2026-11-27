---
api_specs:
- filename: invokely-openapi-generated.yml
  format: yaml
  label: Invokely API
  slug: invokely-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/_ae-authored/invokely-openapi-generated.yml
- filename: invokely-rank-api-openapi.yml
  format: yaml
  label: Invokely Rank API
  slug: invokely-rank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/invokely-rank-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A consumer is a person acting for purposes outside their trade, business or profession.
    type: individual
  - text: If you use Invokely for your work or on behalf of a company, you are a business customer, and you confirm that you can accept these terms for that company.
    type: business
  minimum_age:
    text: You must be 18 or over to create an account.
    value: '18'
  restricted_uses:
  - summary: Use in breach of law or third-party rights
    text: use the service in breach of the law or of third-party rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with an emailed link or with Google.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Invokely
provenance_date: '2026-11-09'
provider_name: Invokely
provider_slug: invokely
slug: invokely-eligibility
source_date: '2026-11-09'
source_filename: invokely-eligibility.yml
source_heading: Eligibility
source_page: https://invokely.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invokely\naid: invokely\nurl: https://invokely.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A consumer is a person acting for purposes outside their trade, business or profession.\n- type: business\n  text: If you use Invokely for your work or on behalf of a company, you are a business customer, and you confirm\n    that you can accept these terms for that company.\nrestricted_uses:\n- summary: Use in breach of law or third-party rights\n  text: use the service in breach of the law or of third-party rights.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with an emailed link or with Google.\nminimum_age:\n  value: '18'\n  text: You must be 18 or over to create an account.\n"
source_yaml_url: https://artifacts.apis.io/invokely/eligibility/invokely-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Invokely's own page on 2026-11-09.
synthetic: false
tags:
- Statistics
- Economic Data
- Public Data
- Data API
---
