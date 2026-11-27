---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are utilizing the Services on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk uses
    text: permit use in connection with any purposes or intended application which involves risks or dangers that could lead to death, serious bodily injury, severe physical or property damage
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
name: Govport
provenance_date: '2026-11-09'
provider_name: Govport
provider_slug: govport
slug: govport-eligibility
source_date: '2026-11-09'
source_filename: govport-eligibility.yml
source_heading: Eligibility
source_page: https://www.govport.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Govport\naid: govport\nurl: https://www.govport.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are utilizing the Services on behalf of an organization, you are agreeing to these Terms for that\n    organization\nrestricted_uses:\n- summary: High-risk uses\n  text: permit use in connection with any purposes or intended application which involves risks or dangers that\n    could lead to death, serious bodily injury, severe physical or property damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/govport/eligibility/govport-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Govport's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government Contracting
- GovCon
- Compliance
- Subcontractor Management
- Software-as-a-Service
- GovTech
---
