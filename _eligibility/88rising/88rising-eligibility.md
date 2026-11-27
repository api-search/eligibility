---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States. Those who choose to access the Services from locations outside the United States do so at their own initiative and are responsible for compliance with applicable local laws.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: You must be thirteen (13) years of age or older.
    value: '13'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: We hereby permit you to use the Services for your personal non-commercial use only
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To use certain of the Services, you need to receive an invitation from us to create an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 88rising
provenance_date: '2026-11-09'
provider_name: 88rising
provider_slug: 88rising
slug: 88rising-eligibility
source_date: '2026-11-09'
source_filename: 88rising-eligibility.yml
source_heading: Eligibility
source_page: https://88rising.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 88rising\naid: 88rising\nurl: https://88rising.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States. Those who choose to access the Services from locations\n    outside the United States do so at their own initiative and are responsible for compliance with applicable local\n    laws.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: We hereby permit\
  \ you to use the Services for your personal non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To use certain of the Services, you need to receive an invitation from us to create an account\nminimum_age:\n  value: '13'\n  text: You must be thirteen (13) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/88rising/eligibility/88rising-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from 88rising's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Entertainment
- Music
- Record Label
- Live Events
- Content
- Marketing
---
