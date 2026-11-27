---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not incorporated, located, or ordinarily resident in a country or territory subject to a comprehensive U.S. Government embargo (currently, Cuba, Iran, North Korea, Syria, or the Crimea, Donetsk People’s Republic, or Luhansk People’s Republic regions of Ukraine)
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF AN ENTITY, ALL REFERENCES TO “YOU” OR “YOUR” IN THESE TERMS WILL ALSO BE DEEMED TO REFER TO SUCH ENTITY.
    type: business
  minimum_age:
    text: YOU ARE AT LEAST 18 YEARS OLD OR THE LEGAL AGE TO FORM A BINDING CONTRACT
    value: '18'
  restricted_uses:
  - summary: Not for high-risk regulated applications
    text: THE SERVICE IS NOT DESIGNED OR LICENSED FOR USE IN HIGH-RISK, SAFETY-CRITICAL, MEDICAL, LEGAL, FINANCIAL, EMPLOYMENT, OR SIMILAR REGULATED APPLICATIONS.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must provide true, accurate, current, and complete information (“Registration Data”)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arena Intelligence
provenance_date: '2026-11-09'
provider_name: Arena Intelligence
provider_slug: arena-intelligence
slug: arena-intelligence-eligibility
source_date: '2026-11-09'
source_filename: arena-intelligence-eligibility.yml
source_heading: Eligibility
source_page: https://platform.arena.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arena Intelligence\naid: arena-intelligence\nurl: https://platform.arena.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not incorporated, located, or ordinarily resident in a country or territory subject to a comprehensive\n    U.S. Government embargo (currently, Cuba, Iran, North Korea, Syria, or the Crimea, Donetsk People’s Republic,\n    or Luhansk People’s Republic regions of Ukraine)\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THESE TERMS ON BEHALF OF AN ENTITY, ALL REFERENCES TO “YOU” OR “YOUR” IN THESE\n    TERMS WILL ALSO BE DEEMED\
  \ TO REFER TO SUCH ENTITY.\nrestricted_uses:\n- summary: Not for high-risk regulated applications\n  text: THE SERVICE IS NOT DESIGNED OR LICENSED FOR USE IN HIGH-RISK, SAFETY-CRITICAL, MEDICAL, LEGAL, FINANCIAL,\n    EMPLOYMENT, OR SIMILAR REGULATED APPLICATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must provide true, accurate, current, and complete information (“Registration Data”)\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST 18 YEARS OLD OR THE LEGAL AGE TO FORM A BINDING CONTRACT\n"
source_yaml_url: https://artifacts.apis.io/arena-intelligence/eligibility/arena-intelligence-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Arena Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Policy
- Advocacy
- Campaign
- Government
---
