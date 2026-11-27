---
api_specs:
- filename: google-custom-search-cse-api-openapi.yml
  format: yaml
  label: Google Custom Search Custom Search Cse API
  slug: google-custom-search-cse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-custom-search/openapi/google-custom-search-cse-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs ... if ... (b) you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
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
name: Google Custom Search
provenance_date: '2026-11-09'
provider_name: Google Custom Search
provider_slug: google-custom-search
slug: google-custom-search-eligibility
source_date: '2026-11-09'
source_filename: google-custom-search-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Custom Search\naid: google-custom-search\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs ... if ... (b) you are a person barred from using or receiving the APIs under the\n    applicable laws of the United States or other countries including the country in which you are resident or from\n    which you use the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n\
  - summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-custom-search/eligibility/google-custom-search-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Google Custom Search's own page on 2026-11-09.
synthetic: false
tags:
- Custom Search
- Google
- Image Search
- Search
- Web Search
---
