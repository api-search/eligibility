---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Avec makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR, IF YOU ARE ACCESSING OR USING THE SERVICE ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS.
    type: business
  minimum_age:
    text: You shall monitor your Account to restrict use by anyone under the age of 16, and you will accept full responsibility for any unauthorized use of the Service by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: HIPAA protected health information
    text: If you are (or become) a “covered entity” or “business associate” as defined in HIPAA, you will not use the Service for any purpose or in any manner involving Making Available protected health information to Avec.
  - summary: ITAR-controlled data
    text: use the Service to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: High-risk activities
    text: use the Service for any activities where the use or failure of the Service could lead to death, personal injury, or environmental damage
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
name: Avec
provenance_date: '2026-11-09'
provider_name: Avec
provider_slug: avec
slug: avec-eligibility
source_date: '2026-11-09'
source_filename: avec-eligibility.yml
source_heading: Eligibility
source_page: https://www.avec.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avec\naid: avec\nurl: https://www.avec.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Avec makes no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THIS AGREEMENT PERSONALLY OR, IF YOU ARE ACCESSING OR USING THE SERVICE\n    ON BEHALF OF AN ENTITY, ON BEHALF OF THE ENTITY IDENTIFIED IN THE ACCOUNT REGISTRATION PROCESS.\nrestricted_uses:\n- summary: HIPAA protected health information\n  text: If you are (or become) a “covered entity”\
  \ or “business associate” as defined in HIPAA, you will not use\n    the Service for any purpose or in any manner involving Making Available protected health information to Avec.\n- summary: ITAR-controlled data\n  text: use the Service to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: High-risk activities\n  text: use the Service for any activities where the use or failure of the Service could lead to death, personal\n    injury, or environmental damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You shall monitor your Account to restrict use by anyone under the age of 16, and you will accept full responsibility\n    for any unauthorized use of the Service by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/avec/eligibility/avec-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Avec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Productivity
- Artificial Intelligence
- Gmail
- Email Management
- Consumer Applications
- iOS
---
