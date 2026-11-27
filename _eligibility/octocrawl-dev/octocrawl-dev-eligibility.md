---
api_specs:
- filename: octocrawl-dev-openapi-generated.yml
  format: yaml
  label: octocrawl-dev API
  slug: octocrawl-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octocrawl-dev/openapi/_ae-authored/octocrawl-dev-openapi-generated.yml
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
  - summary: Private or reserved addresses and login-gated pages
    text: It refuses private and reserved network addresses, pages whose robots.txt does not allow it or cannot be reached, and pages that ask for a login or show a verification challenge.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An account makes its own keys in its dashboard, and keys can be revoked.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: octocrawl-dev
provenance_date: '2026-11-10'
provider_name: octocrawl-dev
provider_slug: octocrawl-dev
slug: octocrawl-dev-eligibility
source_date: '2026-11-10'
source_filename: octocrawl-dev-eligibility.yml
source_heading: Eligibility
source_page: https://octocrawl.dev/docs/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: octocrawl-dev\naid: octocrawl-dev\nurl: https://octocrawl.dev/docs/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Private or reserved addresses and login-gated pages\n  text: It refuses private and reserved network addresses, pages whose robots.txt does not allow it or cannot be\n    reached, and pages that ask for a login or show a verification challenge.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An account makes its own keys in its dashboard, and keys can be revoked.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/octocrawl-dev/eligibility/octocrawl-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from octocrawl-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Software-as-a-Service
- Automation
---
