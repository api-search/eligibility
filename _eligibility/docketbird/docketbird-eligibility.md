---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When you subscribe to a DocketBird business plan, it includes a specified number of seats.
    type: business
  minimum_age:
    text: You will not use DocketBird if you are under 13.
    value: '13'
  restricted_uses:
  - summary: Commercial use other than practice of law
    text: You will not use DocketBird for commercial purposes other than the practice of law.
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
name: DocketBird
provenance_date: '2026-11-09'
provider_name: DocketBird
provider_slug: docketbird
slug: docketbird-eligibility
source_date: '2026-11-09'
source_filename: docketbird-eligibility.yml
source_heading: Eligibility
source_page: https://www.docketbird.com/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DocketBird\naid: docketbird\nurl: https://www.docketbird.com/terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: When you subscribe to a DocketBird business plan, it includes a specified number of seats.\nrestricted_uses:\n- summary: Commercial use other than practice of law\n  text: You will not use DocketBird for commercial purposes other than the practice of law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You will not use DocketBird if you are under\
  \ 13.\n"
source_yaml_url: https://artifacts.apis.io/docketbird/eligibility/docketbird-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DocketBird's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Court-Filing
- Document Management
- Automation
---
