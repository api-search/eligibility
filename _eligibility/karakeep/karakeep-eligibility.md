---
api_specs:
- filename: karakeep-openapi-generated.yml
  format: yaml
  label: Karakeep API
  slug: karakeep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karakeep/openapi/_ae-authored/karakeep-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each account is intended for use by a single individual.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Scraping outside API
    text: Use automated tools to scrape, crawl, or extract data from the Service beyond what is provided through our API.
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
name: Karakeep
provenance_date: '2026-11-09'
provider_name: Karakeep
provider_slug: karakeep
slug: karakeep-eligibility
source_date: '2026-11-09'
source_filename: karakeep-eligibility.yml
source_heading: Eligibility
source_page: https://karakeep.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Karakeep\naid: karakeep\nurl: https://karakeep.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each account is intended for use by a single individual.\nrestricted_uses:\n- summary: Scraping outside API\n  text: Use automated tools to scrape, crawl, or extract data from the Service beyond what is provided through our\n    API.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/karakeep/eligibility/karakeep-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Karakeep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bookmarking
- Artificial Intelligence
- Collaboration
- Open Source
---
