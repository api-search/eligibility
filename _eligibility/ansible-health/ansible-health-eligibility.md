---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that all products, services, and/or material described on the Services are appropriate or available for use in locations outside the United States or all states and territories within the United States.
  entity_types:
  - text: You may use the Services only for your own personal, non-commercial use.
    type: individual
  minimum_age:
    text: The Services are not intended for children. If you are under 18 years of age, please do not use or access the Services at any time or in any manner.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You may use the Services only for your own personal, non-commercial use.
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
name: Ansible Health
provenance_date: '2026-11-09'
provider_name: Ansible Health
provider_slug: ansible-health
slug: ansible-health-eligibility
source_date: '2026-11-09'
source_filename: ansible-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.ansiblehealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ansible Health\naid: ansible-health\nurl: https://www.ansiblehealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that all products, services, and/or material described on the Services are appropriate\n    or available for use in locations outside the United States or all states and territories within the United\n    States.\nentity_types:\n- type: individual\n  text: You may use the Services only for your own personal, non-commercial use.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You may use the Services\
  \ only for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for children. If you are under 18 years of age, please do not use or access\n    the Services at any time or in any manner.\n"
source_yaml_url: https://artifacts.apis.io/ansible-health/eligibility/ansible-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ansible Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- COPD
- Chronic Care
- Remote Patient Monitoring
- Pulmonary
---
