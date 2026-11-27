---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Service is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Health and safety critical uses
    text: THE AVATOUR PLATFORM CANNOT BE USED IN ANY MANNER CRITICAL TO HEALTH AND/OR SECURITY OF OTHER PEOPLE AND PROPERTY (E.G., SURGERY, AVIATION, OR ANY OTHER APPLICATIONS INTENDED TO SUPPORT OR SUSTAIN LIFE).
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
name: AVATOUR
provenance_date: '2026-11-09'
provider_name: AVATOUR
provider_slug: avatour
slug: avatour-eligibility
source_date: '2026-11-09'
source_filename: avatour-eligibility.yml
source_heading: Eligibility
source_page: https://avatour.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AVATOUR\naid: avatour\nurl: https://avatour.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Health and safety critical uses\n  text: THE AVATOUR PLATFORM CANNOT BE USED IN ANY MANNER CRITICAL TO HEALTH AND/OR SECURITY OF OTHER PEOPLE AND\n    PROPERTY (E.G., SURGERY, AVIATION, OR ANY OTHER APPLICATIONS INTENDED TO SUPPORT OR SUSTAIN LIFE).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: The Service is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/avatour/eligibility/avatour-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AVATOUR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- VideoCollaboration
- Remote Inspection
- Virtual Tours
- Artificial Intelligence
---
