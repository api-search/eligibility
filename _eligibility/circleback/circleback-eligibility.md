---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CircleBack makes no representation that content, data, information or other similar materials made available in, on or through our Sites, Applications, including Mobile Applications, and Services are appropriate or available for use in your location.
  entity_types:
  - text: (1) are 18 years of age or older;
    type: individual
  minimum_age:
    text: (1) are 18 years of age or older;
    value: '18'
  restricted_uses:
  - summary: Privacy and anti-spam law compliance
    text: Use any data associated with CircleBack databases in violation of any local privacy restrictions, for example CAN-SPAM, CASL, or GDPR
  - summary: Export control restrictions
    text: You shall not, directly or indirectly, sell, export, re-export, transfer, divert, or otherwise dispose of any software or service to any end-user without obtaining the required authorizations from the appropriate government authorities.
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
name: CircleBack
provenance_date: '2026-11-09'
provider_name: CircleBack
provider_slug: circleback
slug: circleback-eligibility
source_date: '2026-11-09'
source_filename: circleback-eligibility.yml
source_heading: Eligibility
source_page: https://circleback.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CircleBack\naid: circleback\nurl: https://circleback.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CircleBack makes no representation that content, data, information or other similar materials made available\n    in, on or through our Sites, Applications, including Mobile Applications, and Services are appropriate or available\n    for use in your location.\nentity_types:\n- type: individual\n  text: (1) are 18 years of age or older;\nrestricted_uses:\n- summary: Privacy and anti-spam law compliance\n  text: Use any data associated with CircleBack databases in\
  \ violation of any local privacy restrictions, for example\n    CAN-SPAM, CASL, or GDPR\n- summary: Export control restrictions\n  text: You shall not, directly or indirectly, sell, export, re-export, transfer, divert, or otherwise dispose of\n    any software or service to any end-user without obtaining the required authorizations from the appropriate government\n    authorities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (1) are 18 years of age or older;\n"
source_yaml_url: https://artifacts.apis.io/circleback/eligibility/circleback-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CircleBack's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
