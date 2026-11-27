---
api_specs:
- filename: pulpminer-com-openapi-generated.yml
  format: yaml
  label: pulpminer-com API
  slug: pulpminer-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pulpminer-com/openapi/_ae-authored/pulpminer-com-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To use PulpMiner, you must be at least 13 years old.
    value: '13'
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
name: pulpminer-com
provenance_date: '2026-11-10'
provider_name: pulpminer-com
provider_slug: pulpminer-com
slug: pulpminer-com-eligibility
source_date: '2026-11-10'
source_filename: pulpminer-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pulpminer.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pulpminer-com\naid: pulpminer-com\nurl: https://www.pulpminer.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To use PulpMiner, you must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/pulpminer-com/eligibility/pulpminer-com-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from pulpminer-com's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Real-Time
- JSON
- Low-Code
---
