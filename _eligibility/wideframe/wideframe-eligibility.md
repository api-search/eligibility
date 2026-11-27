---
claim_count: 3
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
  - summary: Adult and sexually explicit content
    text: Adult or sexually explicit content — pornography, sexually suggestive material, or any content produced for the purpose of sexual gratification, including imagery, video, audio, or text.
  - summary: Illegal or illicit activity
    text: Facilitate any illegal or illicit activity, including the sale of controlled substances, weapons, or stolen goods
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Wideframe, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wideframe
provenance_date: '2026-11-10'
provider_name: Wideframe
provider_slug: wideframe
slug: wideframe-eligibility
source_date: '2026-11-10'
source_filename: wideframe-eligibility.yml
source_heading: Eligibility
source_page: https://try.wideframe.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wideframe\naid: wideframe\nurl: https://try.wideframe.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult and sexually explicit content\n  text: Adult or sexually explicit content — pornography, sexually suggestive material, or any content produced\n    for the purpose of sexual gratification, including imagery, video, audio, or text.\n- summary: Illegal or illicit activity\n  text: Facilitate any illegal or illicit activity, including the sale of controlled substances, weapons, or stolen\n    goods\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Wideframe, you must create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wideframe/eligibility/wideframe-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Wideframe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Video Editing
- Media
- Content Production
- AI Agents
- Desktop Application
---
