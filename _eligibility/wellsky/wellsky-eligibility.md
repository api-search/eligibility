---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer and ClearCare are independent contractors
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted access by Authorized Users
    text: Company shall identify to ClearCare the Company employees that will be provided password protected access to the Licensed API
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
name: WellSky
provenance_date: '2026-11-10'
provider_name: WellSky
provider_slug: wellsky
slug: wellsky-eligibility
source_date: '2026-11-10'
source_filename: wellsky-eligibility.yml
source_heading: Eligibility
source_page: https://wellsky.com/clearcare-connect-api-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WellSky\naid: wellsky\nurl: https://wellsky.com/clearcare-connect-api-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer and ClearCare are independent contractors\nrestricted_uses:\n- summary: Restricted access by Authorized Users\n  text: Company shall identify to ClearCare the Company employees that will be provided password protected access\n    to the Licensed API\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wellsky/eligibility/wellsky-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from WellSky's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Home Care
- Hospice
- Care Coordination
- FHIR
- Clinical Documentation
- Billing
- Electronic Health Records
---
