---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual ("Worker") applying to full-time jobs via the Bacon Platform
    type: individual
  - text: The App is for the use of Workers and Businesses only for the purpose of contracting for work.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only for contracting for work
    text: The App is for the use of Workers and Businesses only for the purpose of contracting for work.
  - summary: No recruiting for unaffiliated services
    text: The App may not be used to gather information to recruit for another website or service or to solicit, advertise, or contact others for employment, contracting, or any other purpose for a business not affiliated with Bacon without express written permission from Bacon.
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
name: Bacon
provenance_date: '2026-11-09'
provider_name: Bacon
provider_slug: bacon
slug: bacon-eligibility
source_date: '2026-11-09'
source_filename: bacon-eligibility.yml
source_heading: Eligibility
source_page: https://www.baconwork.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bacon\naid: bacon\nurl: https://www.baconwork.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual (\"Worker\") applying to full-time jobs via the Bacon Platform\n- type: business\n  text: The App is for the use of Workers and Businesses only for the purpose of contracting for work.\nrestricted_uses:\n- summary: Only for contracting for work\n  text: The App is for the use of Workers and Businesses only for the purpose of contracting for work.\n- summary: No recruiting for unaffiliated services\n  text: The App\
  \ may not be used to gather information to recruit for another website or service or to solicit, advertise,\n    or contact others for employment, contracting, or any other purpose for a business not affiliated with Bacon\n    without express written permission from Bacon.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bacon/eligibility/bacon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Bacon's own page on 2026-11-09.
synthetic: false
tags:
- GigWork
- Staffing
- On-Demand
- Marketplace
- Utah
---
