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
  - summary: Unauthorised data access
    text: use anacraft to reach analytics data you are not authorised to see
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A Google account with access to at least one Google Analytics 4 property.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: anacraft
provenance_date: '2026-11-09'
provider_name: anacraft
provider_slug: anacraft-dev
slug: anacraft-dev-eligibility
source_date: '2026-11-09'
source_filename: anacraft-dev-eligibility.yml
source_heading: Eligibility
source_page: https://anacraft.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: anacraft\naid: anacraft-dev\nurl: https://anacraft.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorised data access\n  text: use anacraft to reach analytics data you are not authorised to see\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A Google account with access to at least one Google Analytics 4 property.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anacraft-dev/eligibility/anacraft-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from anacraft's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Google Analytics
- MCP
- Open Source
- Dashboards
- Company
---
