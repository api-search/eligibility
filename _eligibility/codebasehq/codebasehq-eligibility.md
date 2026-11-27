---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a Consumer, you have a cooling-off period in which you can cancel certain Services.
    type: individual
  - text: Consumer means an individual acting for purposes which are wholly or mainly outside that individual's trade, business, craft or profession
    type: business
  minimum_age:
    text: If you are under 16, we do not agree to provide the Services to you. Similarly, we do not agree to provide the Services to bots or scripts.
    value: '16'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You must not use the Services in any way that causes detriment to other users of our services or to our network or infrastructure.
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
name: Codebase
provenance_date: '2026-11-09'
provider_name: Codebase
provider_slug: codebasehq
slug: codebasehq-eligibility
source_date: '2026-11-09'
source_filename: codebasehq-eligibility.yml
source_heading: Eligibility
source_page: https://www.codebasehq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codebase\naid: codebasehq\nurl: https://www.codebasehq.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a Consumer, you have a cooling-off period in which you can cancel certain Services.\n- type: business\n  text: Consumer means an individual acting for purposes which are wholly or mainly outside that individual's trade,\n    business, craft or profession\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You must not use the Services in any way that causes detriment to other users of our services\
  \ or to our\n    network or infrastructure.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under 16, we do not agree to provide the Services to you. Similarly, we do not agree to provide\n    the Services to bots or scripts.\n"
source_yaml_url: https://artifacts.apis.io/codebasehq/eligibility/codebasehq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Codebase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Version Control
- Mercurial
- Subversion
- Project Management
- Ticketing
---
