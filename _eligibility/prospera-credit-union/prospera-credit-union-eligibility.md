---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: As a federal credit union, we require you to provide a permanent residential address in order to become a member and to open a retail deposit account.
  entity_types:
  - text: you may open a retail deposit account at any of our branch locations as long as you meet certain conditions.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent account use
    text: We reasonably believe the account will be used for illegal or fraudulent purposes;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Present documents to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prospera Credit Union
provenance_date: '2026-11-10'
provider_name: Prospera Credit Union
provider_slug: prospera-credit-union
slug: prospera-credit-union-eligibility
source_date: '2026-11-10'
source_filename: prospera-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://www.prospera.ca/Policies/Legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prospera Credit Union\naid: prospera-credit-union\nurl: https://www.prospera.ca/Policies/Legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: As a federal credit union, we require you to provide a permanent residential address in order to become\n    a member and to open a retail deposit account.\nentity_types:\n- type: individual\n  text: you may open a retail deposit account at any of our branch locations as long as you meet certain conditions.\nrestricted_uses:\n- summary: Illegal or fraudulent account use\n  text: We reasonably believe the account will be\
  \ used for illegal or fraudulent purposes;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Present documents to verify your identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prospera-credit-union/eligibility/prospera-credit-union-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Prospera Credit Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- British Columbia
- Interac
- Open Banking
- Consumer-Driven Banking
---
