---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13; if you are a child under 13, please do not attempt to register for the Services
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You will only use the Services for your own internal, personal, non-commercial use
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
name: ReDEF
provenance_date: '2026-11-10'
provider_name: ReDEF
provider_slug: redef
slug: redef-eligibility
source_date: '2026-11-10'
source_filename: redef-eligibility.yml
source_heading: Eligibility
source_page: https://redef.com/info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReDEF\naid: redef\nurl: https://redef.com/info/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a \"terrorist supporting\" country\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You will only use the Services for your own internal, personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text:\
  \ We do not knowingly collect or solicit personally identifiable information from children under 13; if you\n    are a child under 13, please do not attempt to register for the Services\n"
source_yaml_url: https://artifacts.apis.io/redef/eligibility/redef-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ReDEF's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Curation
- Newsletters
- Content
- Publishing
- Pop Culture
- Podcasts
---
