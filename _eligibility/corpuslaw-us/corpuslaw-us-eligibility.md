---
api_specs:
- filename: corpuslaw-us-account-api-openapi.yml
  format: yaml
  label: Corpus Account API
  slug: corpuslaw-us-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-account-api-openapi.yml
- filename: corpuslaw-us-browse-api-openapi.yml
  format: yaml
  label: Corpus Browse API
  slug: corpuslaw-us-browse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-browse-api-openapi.yml
- filename: corpuslaw-us-coverage-api-openapi.yml
  format: yaml
  label: Corpus Coverage API
  slug: corpuslaw-us-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-coverage-api-openapi.yml
- filename: corpuslaw-us-formation-api-openapi.yml
  format: yaml
  label: Corpus Formation API
  slug: corpuslaw-us-formation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-formation-api-openapi.yml
- filename: corpuslaw-us-general-api-openapi.yml
  format: yaml
  label: Corpus General API
  slug: corpuslaw-us-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-general-api-openapi.yml
- filename: corpuslaw-us-gis-api-openapi.yml
  format: yaml
  label: Corpus GIS API
  slug: corpuslaw-us-gis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-gis-api-openapi.yml
- filename: corpuslaw-us-search-api-openapi.yml
  format: yaml
  label: Corpus Search API
  slug: corpuslaw-us-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: business formation (LLC and, where available, nonprofit corporation) in all 50 states and the District of Columbia
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No attorney-client relationship
    text: No attorney–client relationship is created by using Corpus.
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
name: Corpus
provenance_date: '2026-11-09'
provider_name: Corpus
provider_slug: corpuslaw-us
slug: corpuslaw-us-eligibility
source_date: '2026-11-09'
source_filename: corpuslaw-us-eligibility.yml
source_heading: Eligibility
source_page: https://corpuslaw.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corpus\naid: corpuslaw-us\nurl: https://corpuslaw.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: business formation (LLC and, where available, nonprofit corporation) in all 50 states and the District of\n    Columbia\nentity_types: []\nrestricted_uses:\n- summary: No attorney-client relationship\n  text: No attorney–client relationship is created by using Corpus.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corpuslaw-us/eligibility/corpuslaw-us-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Corpus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Law
- Business Formation
- LLC
- Compliance
- MCP
- AI Agents
---
