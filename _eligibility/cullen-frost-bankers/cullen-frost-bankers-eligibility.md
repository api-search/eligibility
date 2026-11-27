---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Consumer Customer" means a natural person who establishes a Deposit, Loan or other account primarily for personal, family, or household purposes.'
    type: individual
  - text: If I am using Online Banking Services solely for business purposes, certain provisions of this Agreement will not apply to me
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Locations where use is illegal
    text: Accessing the Online Banking Services from locations where its contents or use is illegal is prohibited by Bank.
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
name: Cullen/Frost Bankers
provenance_date: '2026-11-09'
provider_name: Cullen/Frost Bankers
provider_slug: cullen-frost-bankers
slug: cullen-frost-bankers-eligibility
source_date: '2026-11-09'
source_filename: cullen-frost-bankers-eligibility.yml
source_heading: Eligibility
source_page: https://www.frostbank.com/agreements-disclosures/frost-online-banking-agreement-and-disclosure
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cullen/Frost Bankers\naid: cullen-frost-bankers\nurl: https://www.frostbank.com/agreements-disclosures/frost-online-banking-agreement-and-disclosure\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Consumer Customer\" means a natural person who establishes a Deposit, Loan or other account primarily for\n    personal, family, or household purposes.'\n- type: business\n  text: If I am using Online Banking Services solely for business purposes, certain provisions of this Agreement\n    will not apply to me\nrestricted_uses:\n\
  - summary: Locations where use is illegal\n  text: Accessing the Online Banking Services from locations where its contents or use is illegal is prohibited\n    by Bank.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cullen-frost-bankers/eligibility/cullen-frost-bankers-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cullen/Frost Bankers's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Financial Services
- Texas
- Regional Bank
- Commercial Banking
- Treasury Management
- Consumer Banking
---
