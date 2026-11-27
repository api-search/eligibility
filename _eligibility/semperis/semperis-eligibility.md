---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Site is only intended for individuals who are: (a) aged sixteen (16) years or older and (b) possess the legal capacity to enter into these Terms'
    type: individual
  - text: possess the legal authority to enter into these Terms on your and (if applicable, your organization's) behalf
    type: business
  minimum_age:
    text: aged sixteen (16) years or older
    value: '16'
  restricted_uses:
  - summary: Non-personal or commercial purposes
    text: for non-personal or commercial purposes, or for any purpose for which the Site or the Content are not intended
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
name: Semperis
provenance_date: '2026-11-10'
provider_name: Semperis
provider_slug: semperis
slug: semperis-eligibility
source_date: '2026-11-10'
source_filename: semperis-eligibility.yml
source_heading: Eligibility
source_page: https://www.semperis.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Semperis\naid: semperis\nurl: https://www.semperis.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The Site is only intended for individuals who are: (a) aged sixteen (16) years or older and (b) possess\n    the legal capacity to enter into these Terms'\n- type: business\n  text: possess the legal authority to enter into these Terms on your and (if applicable, your organization's) behalf\nrestricted_uses:\n- summary: Non-personal or commercial purposes\n  text: for non-personal or commercial purposes, or for any\
  \ purpose for which the Site or the Content are not intended\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: aged sixteen (16) years or older\n"
source_yaml_url: https://artifacts.apis.io/semperis/eligibility/semperis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Semperis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Identity Security
- Active Directory
- Entra ID
- Okta
- Disaster Recovery
- Threat Detection
---
