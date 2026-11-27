---
claim_count: 4
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
  - summary: Prohibited product categories
    text: Illegal products or services.
  - summary: Adult content
    text: Adult or explicit content.
  - summary: Hacking or malware
    text: Hacking tools, malware, or software designed to harm others.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: submissions are checked before going live and appear as "Waiting for publishing" until then.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AppBoard
provenance_date: '2026-11-09'
provider_name: AppBoard
provider_slug: appboard-pro
slug: appboard-pro-eligibility
source_date: '2026-11-09'
source_filename: appboard-pro-eligibility.yml
source_heading: Eligibility
source_page: https://appboard.pro/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppBoard\naid: appboard-pro\nurl: https://appboard.pro/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited product categories\n  text: Illegal products or services.\n- summary: Adult content\n  text: Adult or explicit content.\n- summary: Hacking or malware\n  text: Hacking tools, malware, or software designed to harm others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: submissions are checked before going live and appear as \"Waiting for publishing\" until then.\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appboard-pro/eligibility/appboard-pro-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 4 quoted statements, read from AppBoard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Discovery
- Free
- Community
---
