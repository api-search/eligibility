---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services are offered only for your personal use, and not for any commercial use or the use or benefit of any third party.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 16 years of age. If you are under age 16, you may not, under any circumstances or for any reason, use the Services.
    value: '16'
  restricted_uses:
  - summary: No commercial use
    text: the Services are offered only for your personal use, and not for any commercial use or the use or benefit of any third party.
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
name: Instapaper
provenance_date: '2026-11-09'
provider_name: Instapaper
provider_slug: instapaper
slug: instapaper-eligibility
source_date: '2026-11-09'
source_filename: instapaper-eligibility.yml
source_heading: Eligibility
source_page: https://www.instapaper.com/about-legal/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instapaper\naid: instapaper\nurl: https://www.instapaper.com/about-legal/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the Services are offered only for your personal use, and not for any commercial use or the use or benefit\n    of any third party.\nrestricted_uses:\n- summary: No commercial use\n  text: the Services are offered only for your personal use, and not for any commercial use or the use or benefit\n    of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '16'\n  text: You represent and warrant that you are at least 16 years of age. If you are under age 16, you may not, under\n    any circumstances or for any reason, use the Services.\n"
source_yaml_url: https://artifacts.apis.io/instapaper/eligibility/instapaper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Instapaper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Read-it-later
- Productivity
- Web Service
- Bookmarking
---
