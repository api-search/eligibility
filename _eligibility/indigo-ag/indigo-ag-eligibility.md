---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The information on the Site is intended only for use by residents of the United States.
  entity_types:
  - text: This Internet site (“Site”), including all the content it contains, is provided to individuals, as well as representatives of business entities
    type: individual
  - text: This Internet site (“Site”), including all the content it contains, is provided to individuals, as well as representatives of business entities
    type: business
  minimum_age:
    text: By continuing Your use of this Site You represent that You are not under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use this Site only for lawful purposes and in accordance with the Terms of Use.
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
name: Indigo Agriculture
provenance_date: '2026-11-09'
provider_name: Indigo Agriculture
provider_slug: indigo-ag
slug: indigo-ag-eligibility
source_date: '2026-11-09'
source_filename: indigo-ag-eligibility.yml
source_heading: Eligibility
source_page: https://www.indigoag.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Indigo Agriculture\naid: indigo-ag\nurl: https://www.indigoag.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The information on the Site is intended only for use by residents of the United States.\nentity_types:\n- type: individual\n  text: This Internet site (“Site”), including all the content it contains, is provided to individuals, as well\n    as representatives of business entities\n- type: business\n  text: This Internet site (“Site”), including all the content it contains, is provided to individuals, as well\n    as representatives of business entities\n\
  restricted_uses:\n- summary: Lawful purposes only\n  text: You may use this Site only for lawful purposes and in accordance with the Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: By continuing Your use of this Site You represent that You are not under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/indigo-ag/eligibility/indigo-ag-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Indigo Agriculture's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- AgTech
- Microbials
- Soil Carbon
- MRV
- Scope 3
- Sustainability
---
