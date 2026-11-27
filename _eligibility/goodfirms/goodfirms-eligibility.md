---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users must be 18 years of age or older in order to use Goodfirms and its affiliated platforms and services.
    type: individual
  minimum_age:
    text: Users must be 18 years of age or older in order to use Goodfirms and its affiliated platforms and services.
    value: '18'
  restricted_uses:
  - summary: Reviews of employer competitors
    text: Post reviews on products/services that are offered by your current employers or on services/products by direct competitors of your employers or any other product/service having a conflict of interest with you.
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
name: GoodFirms
provenance_date: '2026-11-09'
provider_name: GoodFirms
provider_slug: goodfirms
slug: goodfirms-eligibility
source_date: '2026-11-09'
source_filename: goodfirms-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodfirms.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoodFirms\naid: goodfirms\nurl: https://www.goodfirms.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users must be 18 years of age or older in order to use Goodfirms and its affiliated platforms and services.\nrestricted_uses:\n- summary: Reviews of employer competitors\n  text: Post reviews on products/services that are offered by your current employers or on services/products by\n    direct competitors of your employers or any other product/service having a conflict of interest with you.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be 18 years of age or older in order to use Goodfirms and its affiliated platforms and services.\n"
source_yaml_url: https://artifacts.apis.io/goodfirms/eligibility/goodfirms-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from GoodFirms's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- IT Services
- Software Reviews
---
