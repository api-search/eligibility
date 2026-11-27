---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer in the European Union, you may withdraw from a new paid subscription within 14 days of buying it by emailing us
    type: individual
  - text: If you use the Service for business purposes, you agree to indemnify us against claims by third parties
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized access and abuse
    text: Get past authentication, paywalls or other access controls on sites you do not own or have permission to access.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the API you must create an account and confirm your email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: urlpipe-dev
provenance_date: '2026-11-10'
provider_name: urlpipe-dev
provider_slug: urlpipe-dev
slug: urlpipe-dev-eligibility
source_date: '2026-11-10'
source_filename: urlpipe-dev-eligibility.yml
source_heading: Eligibility
source_page: https://urlpipe.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: urlpipe-dev\naid: urlpipe-dev\nurl: https://urlpipe.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer in the European Union, you may withdraw from a new paid subscription within 14 days\n    of buying it by emailing us\n- type: business\n  text: If you use the Service for business purposes, you agree to indemnify us against claims by third parties\nrestricted_uses:\n- summary: Unauthorized access and abuse\n  text: Get past authentication, paywalls or other access controls on sites you do not own or have\
  \ permission to\n    access.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the API you must create an account and confirm your email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/urlpipe-dev/eligibility/urlpipe-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from urlpipe-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Data
- Web Scraping
- Markdown
- Screenshots
- Artificial Intelligence
---
