---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site that may be accessed from, displayed on or linked to from your mobile device or PC is not available in all languages or in all countries. We make no representations that the Site is appropriate or available for use in any particular location.
  minimum_age:
    text: You must be 13 or older to access or utilize the Site.
    value: '13'
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
name: Pinion
provenance_date: '2026-11-10'
provider_name: Pinion
provider_slug: pinion
slug: pinion-eligibility
source_date: '2026-11-10'
source_filename: pinion-eligibility.yml
source_heading: Eligibility
source_page: https://www.pinionglobal.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinion\naid: pinion\nurl: https://www.pinionglobal.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site that may be accessed from, displayed on or linked to from your mobile device or PC is not available\n    in all languages or in all countries. We make no representations that the Site is appropriate or available for\n    use in any particular location.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older to access or utilize the\
  \ Site.\n"
source_yaml_url: https://artifacts.apis.io/pinion/eligibility/pinion-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Pinion's own page on 2026-11-10.
synthetic: false
tags:
- Food
- Agriculture
- Consulting
- Advisory
- Finance
---
