---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: located within the United States
  entity_types:
  - text: currently employed at, or affiliated with, a recognized research institution, university, or biotechnology company located within the United States
    type: business
  - text: recognized research institution, university
    type: nonprofit
  minimum_age:
    text: individuals who are at least 21 years of age
    value: '21'
  restricted_uses:
  - summary: Sponsor employees and families excluded
    text: Employees, contractors, and immediate family members of Cell Microsystems, Inc. (“Sponsor”) are not eligible to participate.
  - summary: Fraudulent or violating entries
    text: Disqualify any entry that violates these Terms & Conditions or appears to involve fraudulent activity.
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
name: Cellmicrosystems
provenance_date: '2026-11-09'
provider_name: Cellmicrosystems
provider_slug: cellmicrosystems
slug: cellmicrosystems-eligibility
source_date: '2026-11-09'
source_filename: cellmicrosystems-eligibility.yml
source_heading: Eligibility
source_page: https://cellmicrosystems.com/clonechallenge/termsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cellmicrosystems\naid: cellmicrosystems\nurl: https://cellmicrosystems.com/clonechallenge/termsandconditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: located within the United States\nentity_types:\n- type: business\n  text: currently employed at, or affiliated with, a recognized research institution, university, or biotechnology\n    company located within the United States\n- type: nonprofit\n  text: recognized research institution, university\nrestricted_uses:\n- summary: Sponsor employees and families excluded\n  text: Employees, contractors, and immediate family\
  \ members of Cell Microsystems, Inc. (“Sponsor”) are not eligible\n    to participate.\n- summary: Fraudulent or violating entries\n  text: Disqualify any entry that violates these Terms & Conditions or appears to involve fraudulent activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: individuals who are at least 21 years of age\n"
source_yaml_url: https://artifacts.apis.io/cellmicrosystems/eligibility/cellmicrosystems-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Cellmicrosystems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Single Cell
- Research
- Instruments
---
