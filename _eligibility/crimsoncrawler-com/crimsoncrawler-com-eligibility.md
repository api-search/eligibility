---
api_specs:
- filename: crimsoncrawler-com-openapi-generated.yml
  format: yaml
  label: crimsoncrawler-com API
  slug: crimsoncrawler-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimsoncrawler-com/openapi/_ae-authored/crimsoncrawler-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, whichever is greater, to use Crimson Crawler and to agree to these terms.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Unauthorized testing
    text: You must not use it for unauthorized testing of systems you do not have permission to evaluate, or for anything unlawful.
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
name: crimsoncrawler-com
provenance_date: '2026-11-09'
provider_name: crimsoncrawler-com
provider_slug: crimsoncrawler-com
slug: crimsoncrawler-com-eligibility
source_date: '2026-11-09'
source_filename: crimsoncrawler-com-eligibility.yml
source_heading: Eligibility
source_page: https://crimsoncrawler.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crimsoncrawler-com\naid: crimsoncrawler-com\nurl: https://crimsoncrawler.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, whichever is greater, to use Crimson\n    Crawler and to agree to these terms.\nrestricted_uses:\n- summary: Unauthorized testing\n  text: You must not use it for unauthorized testing of systems you do not have permission to evaluate, or for anything\n    unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/crimsoncrawler-com/eligibility/crimsoncrawler-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from crimsoncrawler-com's own page on 2026-11-09.
synthetic: false
tags:
- CVE
- Threat Intelligence
- Security
- Data API
---
