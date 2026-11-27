---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site can be accessed from any of the United States and from other countries worldwide.
  minimum_age:
    text: the Site is not intended or designed to attract children under the age of 18.
    value: null
  restricted_uses:
  - summary: No access from locations where content is illegal
    text: accessing them from territories where their contents are illegal is prohibited.
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
name: Cmtsolutions
provenance_date: '2026-11-09'
provider_name: Cmtsolutions
provider_slug: cmtsolutions
slug: cmtsolutions-eligibility
source_date: '2026-11-09'
source_filename: cmtsolutions-eligibility.yml
source_heading: Eligibility
source_page: https://www.careviso.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cmtsolutions\naid: cmtsolutions\nurl: https://www.careviso.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site can be accessed from any of the United States and from other countries worldwide.\nentity_types: []\nrestricted_uses:\n- summary: No access from locations where content is illegal\n  text: accessing them from territories where their contents are illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: the Site is not intended or designed to attract children under\
  \ the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/cmtsolutions/eligibility/cmtsolutions-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cmtsolutions's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Transparency
- Automation
---
