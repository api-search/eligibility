---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not live in an area in which use of the Qlik Sites is prohibited by applicable law
  entity_types:
  - text: if you access the Qlik Sites on behalf of a legal entity, to that entity.
    type: business
  minimum_age:
    text: You must be at least sixteen (16) years old to have a Qlik Account
    value: '16'
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
name: Qlik
provenance_date: '2026-11-10'
provider_name: Qlik
provider_slug: qlikview-com
slug: qlikview-com-eligibility
source_date: '2026-11-10'
source_filename: qlikview-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.qlik.com/us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qlik\naid: qlikview-com\nurl: https://www.qlik.com/us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not live in an area in which use of the Qlik Sites is prohibited by applicable law\nentity_types:\n- type: business\n  text: if you access the Qlik Sites on behalf of a legal entity, to that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least sixteen (16) years old to have a Qlik Account\n"
source_yaml_url: https://artifacts.apis.io/qlikview-com/eligibility/qlikview-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Qlik's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Data Integration
- Cloud Analytics
- Enterprise Software
---
