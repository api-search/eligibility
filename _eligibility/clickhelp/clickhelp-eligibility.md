---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for use by business entities only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated abusive access
    text: You will not intentionally facilitate automated or abusive access to the Services that artificially inflates CAPs usage
  - summary: Personal data in AI features
    text: Client must not submit to any AI feature any Personal Data, Special Categories of Personal Data, PHI, payment card data, or other regulated/sensitive information.
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
name: ClickHelp
provenance_date: '2026-11-09'
provider_name: ClickHelp
provider_slug: clickhelp
slug: clickhelp-eligibility
source_date: '2026-11-09'
source_filename: clickhelp-eligibility.yml
source_heading: Eligibility
source_page: https://clickhelp.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClickHelp\naid: clickhelp\nurl: https://clickhelp.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for use by business entities only.\nrestricted_uses:\n- summary: Automated abusive access\n  text: You will not intentionally facilitate automated or abusive access to the Services that artificially inflates\n    CAPs usage\n- summary: Personal data in AI features\n  text: Client must not submit to any AI feature any Personal Data, Special Categories of Personal Data, PHI, payment\n    card\
  \ data, or other regulated/sensitive information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clickhelp/eligibility/clickhelp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ClickHelp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Documentation
- Artificial Intelligence
- Software-as-a-Service
- Technical Writing
---
