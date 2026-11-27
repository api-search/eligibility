---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Services are not available in, and may not be accessed from, jurisdictions where Material Bank does not distribute Samples, or where prohibited by law.
  entity_types:
  - text: Access to a particular region may be limited to Users (and the companies or firms they represent) that maintain an office in that region
    type: business
  - text: The Services are intended for professional Users in architecture and design and related professionals such as contractors, resource librarians, material specifiers and others.
    type: individual
  minimum_age:
    text: The Services are intended for Users 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Samples only for Project specification or evaluation
    text: Samples may only be ordered in connection with a Project for specification or evaluation purposes.
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
name: Material Bank
provenance_date: '2026-11-10'
provider_name: Material Bank
provider_slug: material-bank
slug: material-bank-eligibility
source_date: '2026-11-10'
source_filename: material-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.materialbank.com/na/en-US/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Material Bank\naid: material-bank\nurl: https://www.materialbank.com/na/en-US/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Services are not available in, and may not be accessed from, jurisdictions where Material Bank does\n    not distribute Samples, or where prohibited by law.\nentity_types:\n- type: business\n  text: Access to a particular region may be limited to Users (and the companies or firms they represent) that maintain\n    an office in that region\n- type: individual\n  text: The Services are intended for professional Users in architecture and\
  \ design and related professionals such\n    as contractors, resource librarians, material specifiers and others.\nrestricted_uses:\n- summary: Samples only for Project specification or evaluation\n  text: Samples may only be ordered in connection with a Project for specification or evaluation purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for Users 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/material-bank/eligibility/material-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Material Bank's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Materials
- Marketplace
- Architecture
- Interior Design
- Samples
- Building Products
- Sustainability
---
