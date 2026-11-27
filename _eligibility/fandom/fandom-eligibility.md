---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you are of legal age to form a binding contract with the Company
    type: individual
  minimum_age:
    text: or 13 or older (applicable to users located in the rest of the world including the U.K.)
    value: 13 or 16 depending on location
  restricted_uses:
  - summary: No business advertising
    text: Post advertisements or solicitations of business;
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
name: Fandom
provenance_date: '2026-11-09'
provider_name: Fandom
provider_slug: fandom
slug: fandom-eligibility
source_date: '2026-11-09'
source_filename: fandom-eligibility.yml
source_heading: Eligibility
source_page: https://www.fandom.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fandom\naid: fandom\nurl: https://www.fandom.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm that you are of legal age to form a binding contract with the Company\nrestricted_uses:\n- summary: No business advertising\n  text: Post advertisements or solicitations of business;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 or 16 depending on location\n  text: or 13 or older (applicable to users located in the rest of the world including the U.K.)\n"
source_yaml_url: https://artifacts.apis.io/fandom/eligibility/fandom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fandom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Wiki
- MediaWiki
- Media
- Entertainment
- Community
- Content
- Fan Community
---
