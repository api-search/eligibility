---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PicnicHealth makes no claims that the Service may be lawfully viewed, downloaded, or accessed outside of the United States.
  entity_types:
  - text: You may not accept this Agreement and enroll to use our Service if you are not of a legal age in your jurisdiction to form a binding contract with PicnicHealth.
    type: individual
  - text: if you are acting on behalf of a company or entity, that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: You may not accept this Agreement and enroll to use our Service if you are not of a legal age in your jurisdiction to form a binding contract with PicnicHealth.
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use the Platform for lawful purposes.
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
name: PicnicHealth
provenance_date: '2026-11-10'
provider_name: PicnicHealth
provider_slug: picnichealth
slug: picnichealth-eligibility
source_date: '2026-11-10'
source_filename: picnichealth-eligibility.yml
source_heading: Eligibility
source_page: https://picnichealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PicnicHealth\naid: picnichealth\nurl: https://picnichealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PicnicHealth makes no claims that the Service may be lawfully viewed, downloaded, or accessed outside of\n    the United States.\nentity_types:\n- type: individual\n  text: You may not accept this Agreement and enroll to use our Service if you are not of a legal age in your jurisdiction\n    to form a binding contract with PicnicHealth.\n- type: business\n  text: if you are acting on behalf of a company or entity, that you have the authority to bind such entity.\n\
  restricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use the Platform for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not accept this Agreement and enroll to use our Service if you are not of a legal age in your jurisdiction\n    to form a binding contract with PicnicHealth.\n"
source_yaml_url: https://artifacts.apis.io/picnichealth/eligibility/picnichealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from PicnicHealth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Biology
- Health
- Medical Records
- Real-World Data
- Real-World Evidence
- HEOR
- OMOP
- Life Sciences
- Healthcare
---
