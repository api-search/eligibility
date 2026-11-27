---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that you are at least the legal age of majority in your jurisdiction.
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You shall not export BOOQED Platform, Platform Apps, Platform Web Portal, or other Services or the Content, or any information about any of them without the prior written consent of BOOQED
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
name: Booqed
provenance_date: '2026-11-09'
provider_name: Booqed
provider_slug: booqed
slug: booqed-eligibility
source_date: '2026-11-09'
source_filename: booqed-eligibility.yml
source_heading: Eligibility
source_page: https://www.booqed.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Booqed\naid: booqed\nurl: https://www.booqed.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You shall not export BOOQED Platform, Platform Apps, Platform Web Portal, or other Services or the Content,\n    or any information about any of them without the prior written consent of BOOQED\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent that you are at least the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/booqed/eligibility/booqed-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Booqed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Workspace Booking
- Smart Office
- Space Management
- Co-Working
- Meeting Rooms
- Real Estate
- Hardware
---
