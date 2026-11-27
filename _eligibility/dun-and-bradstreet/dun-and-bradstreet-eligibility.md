---
api_specs:
- filename: dun-and-bradstreet-authentication-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Authentication API
  slug: dun-and-bradstreet-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-authentication-api-openapi.yml
- filename: dun-and-bradstreet-data-file-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Data File API
  slug: dun-and-bradstreet-data-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-data-file-api-openapi.yml
- filename: dun-and-bradstreet-enrich-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Enrich API
  slug: dun-and-bradstreet-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-enrich-api-openapi.yml
- filename: dun-and-bradstreet-identity-resolution-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Identity Resolution API
  slug: dun-and-bradstreet-identity-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-identity-resolution-api-openapi.yml
- filename: dun-and-bradstreet-monitoring-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Monitoring API
  slug: dun-and-bradstreet-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-monitoring-api-openapi.yml
- filename: dun-and-bradstreet-multi-process-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Multi-Process API
  slug: dun-and-bradstreet-multi-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-multi-process-api-openapi.yml
- filename: dun-and-bradstreet-research-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Research API
  slug: dun-and-bradstreet-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-research-api-openapi.yml
- filename: dun-and-bradstreet-search-api-openapi.yml
  format: yaml
  label: Dun & Bradstreet Search API
  slug: dun-and-bradstreet-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dun-and-bradstreet/openapi/dun-and-bradstreet-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Individual credit, employment, insurance use
    text: use or permit the use of the information in connection with any individual credit, employment, or insurance applications
  - summary: Illegal, fraudulent or abusive use
    text: Use of an Account for illegal, fraudulent or abusive purposes may be referred to law enforcement authorities without notice to you.
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
name: Dun & Bradstreet
provenance_date: '2026-11-09'
provider_name: Dun & Bradstreet
provider_slug: dun-and-bradstreet
slug: dun-and-bradstreet-eligibility
source_date: '2026-11-09'
source_filename: dun-and-bradstreet-eligibility.yml
source_heading: Eligibility
source_page: https://www.dnb.com/en-us/utilities/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dun & Bradstreet\naid: dun-and-bradstreet\nurl: https://www.dnb.com/en-us/utilities/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Individual credit, employment, insurance use\n  text: use or permit the use of the information in connection with any individual credit, employment, or insurance\n    applications\n- summary: Illegal, fraudulent or abusive use\n  text: Use of an Account for illegal, fraudulent or abusive purposes may be referred to law enforcement authorities\n    without notice to you.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dun-and-bradstreet/eligibility/dun-and-bradstreet-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Dun & Bradstreet's own page on 2026-11-09.
synthetic: false
tags:
- Business Data
- Company Data
- D-U-N-S Number
- Credit
- Risk Management
- Master Data
- Data Enrichment
- Identity Resolution
- Compliance
- Supply Chain
- Sales Intelligence
- Monitoring
---
