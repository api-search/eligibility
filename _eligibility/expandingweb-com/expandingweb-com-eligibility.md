---
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
  - summary: Scanning third-party domains
    text: You may only scan domains you own or are authorised to assess.
  - summary: Spam or disruption
    text: You must not use the site to send spam, probe or disrupt the service
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
name: expandingweb-com
provenance_date: '2026-11-09'
provider_name: expandingweb-com
provider_slug: expandingweb-com
slug: expandingweb-com-eligibility
source_date: '2026-11-09'
source_filename: expandingweb-com-eligibility.yml
source_heading: Eligibility
source_page: https://expandingweb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: expandingweb-com\naid: expandingweb-com\nurl: https://expandingweb.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Scanning third-party domains\n  text: You may only scan domains you own or are authorised to assess.\n- summary: Spam or disruption\n  text: You must not use the site to send spam, probe or disrupt the service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/expandingweb-com/eligibility/expandingweb-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from expandingweb-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
