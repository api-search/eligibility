---
api_specs:
- filename: crawio-com-openapi-generated.yml
  format: yaml
  label: crawio-com API
  slug: crawio-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawio-com/openapi/_ae-authored/crawio-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company, you confirm you may bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal data misuse
    text: collect personal data for spam, surveillance, stalking, or discrimination, or knowingly collect data about children
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
name: crawio-com
provenance_date: '2026-11-09'
provider_name: crawio-com
provider_slug: crawio-com
slug: crawio-com-eligibility
source_date: '2026-11-09'
source_filename: crawio-com-eligibility.yml
source_heading: Eligibility
source_page: https://crawio.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crawio-com\naid: crawio-com\nurl: https://crawio.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company, you confirm you may bind that company.\nrestricted_uses:\n- summary: Personal data misuse\n  text: collect personal data for spam, surveillance, stalking, or discrimination, or knowingly collect data about\n    children\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crawio-com/eligibility/crawio-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from crawio-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Proxy
- Anti-Bot
- Data Extraction
---
