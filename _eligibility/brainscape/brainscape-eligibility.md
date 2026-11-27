---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts are for individuals only and sharing accounts with multiple people, including people at the same organization is strictly forbidden
    type: individual
  - text: Companies, schools, government agencies, and other types of organizations may also enter into license agreements with Brainscape, with prices and payment methods that are negotiated separately from these Terms
    type: business
  minimum_age:
    text: The Service is for users of all ages. For children younger than 13, parental consent is required.
    value: null
  restricted_uses:
  - summary: Solicitation of minors' personal info
    text: Solicit personal information from anyone under 18
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
name: Brainscape
provenance_date: '2026-11-09'
provider_name: Brainscape
provider_slug: brainscape
slug: brainscape-eligibility
source_date: '2026-11-09'
source_filename: brainscape-eligibility.yml
source_heading: Eligibility
source_page: https://www.brainscape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brainscape\naid: brainscape\nurl: https://www.brainscape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Accounts are for individuals only and sharing accounts with multiple people, including people at the same\n    organization is strictly forbidden\n- type: business\n  text: Companies, schools, government agencies, and other types of organizations may also enter into license agreements\n    with Brainscape, with prices and payment methods that are negotiated separately from these Terms\nrestricted_uses:\n- summary: Solicitation\
  \ of minors' personal info\n  text: Solicit personal information from anyone under 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Service is for users of all ages. For children younger than 13, parental consent is required.\n"
source_yaml_url: https://artifacts.apis.io/brainscape/eligibility/brainscape-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Brainscape's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Flashcards
- Learning
- Study Tools
- Mobile App
---
