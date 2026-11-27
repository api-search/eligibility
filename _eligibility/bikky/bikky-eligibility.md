---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting the agreement is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: (f) use or allow the transmission, transfer, export, re-export or other transfer of any product, technology or information it obtains or learns pursuant to this Agreement (or any direct product thereof) in violation of any export control or other laws and regulations of the United States or any other relevant jurisdiction
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
name: Bikky
provenance_date: '2026-11-09'
provider_name: Bikky
provider_slug: bikky
slug: bikky-eligibility
source_date: '2026-11-09'
source_filename: bikky-eligibility.yml
source_heading: Eligibility
source_page: https://www.bikky.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bikky\naid: bikky\nurl: https://www.bikky.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting the agreement is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Export control compliance\n  text: (f) use or allow the transmission, transfer, export, re-export or other transfer of any product, technology\n    or information it obtains or learns pursuant to this Agreement\
  \ (or any direct product thereof) in violation\n    of any export control or other laws and regulations of the United States or any other relevant jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bikky/eligibility/bikky-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Bikky's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Customer Data Platform
- Guest Analytics
- Integration
- Marketing
- Loyalty
---
