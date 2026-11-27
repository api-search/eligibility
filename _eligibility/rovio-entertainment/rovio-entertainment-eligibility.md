---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept these TOS, you represent that you are of the age of majority in your country of residence.
    type: individual
  minimum_age:
    text: If you accept these TOS, you represent that you are of the age of majority in your country of residence.
    value: age of majority
  restricted_uses:
  - summary: No commercial use
    text: Use the Services for commercial purposes, including, but not limited to, to advertising, or solicitation
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
name: Rovio Entertainment
provenance_date: '2026-11-10'
provider_name: Rovio Entertainment
provider_slug: rovio-entertainment
slug: rovio-entertainment-eligibility
source_date: '2026-11-10'
source_filename: rovio-entertainment-eligibility.yml
source_heading: Eligibility
source_page: https://www.rovio.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rovio Entertainment\naid: rovio-entertainment\nurl: https://www.rovio.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you accept these TOS, you represent that you are of the age of majority in your country of residence.\nrestricted_uses:\n- summary: No commercial use\n  text: Use the Services for commercial purposes, including, but not limited to, to advertising, or solicitation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text:\
  \ If you accept these TOS, you represent that you are of the age of majority in your country of residence.\n"
source_yaml_url: https://artifacts.apis.io/rovio-entertainment/eligibility/rovio-entertainment-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rovio Entertainment's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Mobile Games
- Entertainment
- Games
- Finland
- Angry Birds
---
