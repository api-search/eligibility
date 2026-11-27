---
api_specs:
- filename: legal-ge-public-apis-directory-api-openapi.yml
  format: yaml
  label: legal.ge Public APIs Directory API
  slug: legal-ge-public-apis-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legal-ge-public-apis/openapi/legal-ge-public-apis-directory-api-openapi.yml
- filename: legal-ge-public-apis-matching-api-openapi.yml
  format: yaml
  label: legal.ge Public APIs Matching API
  slug: legal-ge-public-apis-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legal-ge-public-apis/openapi/legal-ge-public-apis-matching-api-openapi.yml
- filename: legal-ge-public-apis-law-api-openapi.yml
  format: yaml
  label: legal.ge Public APIs Law API
  slug: legal-ge-public-apis-law-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legal-ge-public-apis/openapi/legal-ge-public-apis-law-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GE
    text: ოპერირებს საქართველოში
  entity_types:
  - text: 18 წლის ან მეტი ასაკის პირებს, რომლებიც ეთანხმებიან წინამდებარე წესებს
    type: individual
  minimum_age:
    text: null
    value: null
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
name: legal.ge Public APIs
provenance_date: '2026-11-09'
provider_name: legal.ge Public APIs
provider_slug: legal-ge-public-apis
slug: legal-ge-public-apis-eligibility
source_date: '2026-11-09'
source_filename: legal-ge-public-apis-eligibility.yml
source_heading: Eligibility
source_page: https://legal.ge/ka/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: legal.ge Public APIs\naid: legal-ge-public-apis\nurl: https://legal.ge/ka/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GE\n  excluded: []\n  text: ოპერირებს საქართველოში\nentity_types:\n- type: individual\n  text: 18 წლის ან მეტი ასაკის პირებს, რომლებიც ეთანხმებიან წინამდებარე წესებს\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/legal-ge-public-apis/eligibility/legal-ge-public-apis-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from legal.ge Public APIs's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Law
- Legal Services
- Directory
- Georgia
- AI Agents
- MCP
- Specialists
- Professional Services
- Marketplace
- Multilingual
- Legal Tech
---
