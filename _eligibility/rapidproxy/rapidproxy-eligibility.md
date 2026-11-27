---
api_specs:
- filename: rapidproxy-rapidproxy-rapid-terminal-uk-network-limited-api-api-openapi.yml
  format: yaml
  label: RapidProxy (RAPID TERMINAL UK NETWORK LIMITED) RapidProxy (RAPID TERMINAL UK NETWORK LIMITED) API
  slug: rapidproxy-rapidproxy-rapid-terminal-uk-network-limited-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rapidproxy/openapi/rapidproxy-rapidproxy-rapid-terminal-uk-network-limited-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company's Services and System are available globally, though certain areas may have restrictions due to regulatory constraints.
  entity_types:
  - text: The Company offers services only to natural persons of legal age.
    type: individual
  - text: The Company offers services only to duly established legal entities.
    type: business
  minimum_age:
    text: The Company offers services only to natural persons of legal age.
    value: legal age
  restricted_uses:
  - summary: Illicit activity and sanctions violations
    text: The Company explicitly prohibits and rejects the use of its Services for any illicit activity, including money laundering, terrorist financing, or violations of trade sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: the Company may ask for identity verification or other information (e.g., verifying a mobile number).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RapidProxy (RAPID TERMINAL UK NETWORK LIMITED)
provenance_date: '2026-11-10'
provider_name: RapidProxy (RAPID TERMINAL UK NETWORK LIMITED)
provider_slug: rapidproxy
slug: rapidproxy-eligibility
source_date: '2026-11-10'
source_filename: rapidproxy-eligibility.yml
source_heading: Eligibility
source_page: https://www.rapidproxy.io/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RapidProxy (RAPID TERMINAL UK NETWORK LIMITED)\naid: rapidproxy\nurl: https://www.rapidproxy.io/terms_of_service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company's Services and System are available globally, though certain areas may have restrictions due\n    to regulatory constraints.\nentity_types:\n- type: individual\n  text: The Company offers services only to natural persons of legal age.\n- type: business\n  text: The Company offers services only to duly established legal entities.\nrestricted_uses:\n- summary: Illicit activity and sanctions violations\n  text: The\
  \ Company explicitly prohibits and rejects the use of its Services for any illicit activity, including\n    money laundering, terrorist financing, or violations of trade sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: the Company may ask for identity verification or other information (e.g., verifying a mobile number).\nminimum_age:\n  value: legal age\n  text: The Company offers services only to natural persons of legal age.\n"
source_yaml_url: https://artifacts.apis.io/rapidproxy/eligibility/rapidproxy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from RapidProxy (RAPID TERMINAL UK NETWORK LIMITED)'s own page on 2026-11-10.
synthetic: false
tags:
- Proxy
- Residential
- Web Scraping
- Data Collection
---
