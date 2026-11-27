---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account is one organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized site crawling
    text: Asking us to crawl a site you have no right to audit, or to get around a site’s own rules, is the one thing that ends an account without notice.
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
name: trakis-io
provenance_date: '2026-11-10'
provider_name: trakis-io
provider_slug: trakis-io
slug: trakis-io-eligibility
source_date: '2026-11-10'
source_filename: trakis-io-eligibility.yml
source_heading: Eligibility
source_page: https://trakis.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: trakis-io\naid: trakis-io\nurl: https://trakis.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: One account is one organization.\nrestricted_uses:\n- summary: Unauthorized site crawling\n  text: Asking us to crawl a site you have no right to audit, or to get around a site’s own rules, is the one thing\n    that ends an account without notice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trakis-io/eligibility/trakis-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from trakis-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SEO
- Audit
- Free
- Artificial Intelligence
---
