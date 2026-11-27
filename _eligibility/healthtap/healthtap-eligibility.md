---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: HEALTHTAP AND THE CONTENT AND SERVICES WERE DEVELOPED FOR USE IN THE UNITED STATES, AND NEITHER WE NOR ANY OF OUR LICENSORS MAKE ANY REPRESENTATION CONCERNING HEALTHTAP AND THE CONTENT OR SERVICES WHEN USED IN ANY OTHER COUNTRY.
  entity_types:
  - text: HealthTap is a service for individuals to use to support their personal health decisions.
    type: individual
  - text: Companies or other organizations may not become registered members or use our Apps through individual members, but we do offer enterprise services for organizations, plans and programs.
    type: business
  minimum_age:
    text: Currently, you must be at least 18 years old to use HealthTap and to participate in a Virtual Consult that you initiate.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: You may use HealthTap for personal, but not for commercial purposes in accordance with all applicable federal, state and local laws.
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
name: HealthTap
provenance_date: '2026-11-09'
provider_name: HealthTap
provider_slug: healthtap
slug: healthtap-eligibility
source_date: '2026-11-09'
source_filename: healthtap-eligibility.yml
source_heading: Eligibility
source_page: https://www.healthtap.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HealthTap\naid: healthtap\nurl: https://www.healthtap.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: HEALTHTAP AND THE CONTENT AND SERVICES WERE DEVELOPED FOR USE IN THE UNITED STATES, AND NEITHER WE NOR ANY\n    OF OUR LICENSORS MAKE ANY REPRESENTATION CONCERNING HEALTHTAP AND THE CONTENT OR SERVICES WHEN USED IN ANY OTHER\n    COUNTRY.\nentity_types:\n- type: individual\n  text: HealthTap is a service for individuals to use to support their personal health decisions.\n- type: business\n  text: Companies or other organizations may not become registered\
  \ members or use our Apps through individual members,\n    but we do offer enterprise services for organizations, plans and programs.\nrestricted_uses:\n- summary: Personal use only\n  text: You may use HealthTap for personal, but not for commercial purposes in accordance with all applicable federal,\n    state and local laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Currently, you must be at least 18 years old to use HealthTap and to participate in a Virtual Consult that\n    you initiate.\n"
source_yaml_url: https://artifacts.apis.io/healthtap/eligibility/healthtap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HealthTap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Telehealth
- Virtual Care
- Healthcare
- Primary Care
- Digital Health
---
