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
  - summary: Export control compliance
    text: you are solely responsible for complying with all applicable export, re-export, and import control laws and regulations
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Addepar, in its sole discretion, may decide to grant you access to the Developer Portal.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Addepar
provenance_date: '2026-11-09'
provider_name: Addepar
provider_slug: addepar
slug: addepar-eligibility
source_date: '2026-11-09'
source_filename: addepar-eligibility.yml
source_heading: Eligibility
source_page: https://developers.addepar.com/docs/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Addepar\naid: addepar\nurl: https://developers.addepar.com/docs/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: you are solely responsible for complying with all applicable export, re-export, and import control laws\n    and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Addepar, in its sole discretion, may decide to grant you access to the Developer Portal.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/addepar/eligibility/addepar-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Addepar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Wealth Management
- Portfolio Management
- Investment Management
- Financial Data
- Family Offices
- RIA
- JSON:API
- REST
---
