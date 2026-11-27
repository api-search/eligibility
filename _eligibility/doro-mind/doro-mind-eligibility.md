---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least eighteen (18) years of age
    type: individual
  - text: IF THE INDIVIDUAL ENTERING INTO THE AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO ON BEHALF OF, OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY, SUCH INDIVIDUAL AND SUCH ENTITY AGREES
    type: business
  minimum_age:
    text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: SUPPORT SERVICES SHOULD NEVER BE USED FOR MEDICAL EMERGENCIES OR URGENT SITUATIONS OR INSTANCES WHERE SOMEONE MAY BE IN DANGER OR REQUIRE IMMEDIATE ASSISTANCE.
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
name: Doro Mind
provenance_date: '2026-11-09'
provider_name: Doro Mind
provider_slug: doro-mind
slug: doro-mind-eligibility
source_date: '2026-11-09'
source_filename: doro-mind-eligibility.yml
source_heading: Eligibility
source_page: https://doromind.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doro Mind\naid: doro-mind\nurl: https://doromind.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least eighteen (18) years of age\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THE AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO ON\n    BEHALF OF, OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY, SUCH INDIVIDUAL\n    AND SUCH ENTITY AGREES\nrestricted_uses:\n- summary: Not for emergencies\n  text: SUPPORT SERVICES SHOULD\
  \ NEVER BE USED FOR MEDICAL EMERGENCIES OR URGENT SITUATIONS OR INSTANCES WHERE SOMEONE\n    MAY BE IN DANGER OR REQUIRE IMMEDIATE ASSISTANCE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST EIGHTEEN (18) YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/doro-mind/eligibility/doro-mind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Doro Mind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Startups
- Public-benefit
- Telehealth
---
