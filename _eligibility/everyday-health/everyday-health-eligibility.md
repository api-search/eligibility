---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: No one under the age of 13 should provide any Personal Information or use our public discussion areas, forums or chats.
    value: '13'
  restricted_uses:
  - summary: Minors cannot make purchases
    text: Minors under the age of 18 are not permitted to make purchases through the Services
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
name: Everyday Health
provenance_date: '2026-11-09'
provider_name: Everyday Health
provider_slug: everyday-health
slug: everyday-health-eligibility
source_date: '2026-11-09'
source_filename: everyday-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.everydayhealth.com/privacyterms/#everyday-health-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everyday Health\naid: everyday-health\nurl: https://www.everydayhealth.com/privacyterms/#everyday-health-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minors cannot make purchases\n  text: Minors under the age of 18 are not permitted to make purchases through the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: No one under the age of 13 should provide any Personal Information or use our public discussion areas, forums\n\
  \    or chats.\n"
source_yaml_url: https://artifacts.apis.io/everyday-health/eligibility/everyday-health-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Everyday Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Consumer Health
- Media
- Publishing
- Content
- Healthcare
- Advertising
- Pharma Marketing
- Pregnancy
- Parenting
---
