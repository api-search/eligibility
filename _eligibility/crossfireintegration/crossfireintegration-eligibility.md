---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant and represent that You are acquiring the right to access and use the Services for the purposes of a business
    type: business
  minimum_age:
    text: null
    value: null
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
name: Sandfield
provenance_date: '2026-11-09'
provider_name: Sandfield
provider_slug: crossfireintegration
slug: crossfireintegration-eligibility
source_date: '2026-11-09'
source_filename: crossfireintegration-eligibility.yml
source_heading: Eligibility
source_page: https://crossfireintegration.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sandfield\naid: crossfireintegration\nurl: https://crossfireintegration.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You warrant and represent that You are acquiring the right to access and use the Services for the purposes\n    of a business\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crossfireintegration/eligibility/crossfireintegration-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Sandfield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- EDI
- Supply Chain
---
