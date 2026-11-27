---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://ventrilo.ai/terms-of-use
    text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    source: https://ventrilo.ai/terms-of-use
    text: We do not knowingly collect or solicit personally identifiable information from children under 18 years of age; if you are a child under 18 years of age, please do not attempt to register for or otherwise use the Services
    value: '18'
  restricted_uses:
  - summary: Election interference and surveillance
    text: 'engage in surveillance: tracking, targeting or reporting on identity, facial recognition, covert tracking, battlefield management, predictive policing'
  - summary: Automated high-risk decisions
    text: make automated decisions in high-risk areas (e.g., employment, credit, housing, insurance) without appropriate human oversight and safeguards
  - summary: Social scoring
    text: assign social/behavioral “scores” to individuals (social scoring) without consent
  - summary: Hazardous applications
    text: any use that is sensitive, critical, unsafe, high-risk, or hazardous
  - source: https://ventrilo.ai/terms-of-use
    summary: Acceptable use restrictions on Input
    text: You represent, warrant, and agree that you will comply with the terms in our Acceptable Use Policy
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
name: Ventrilo.ai
provenance_date: '2026-11-10'
provider_name: Ventrilo.ai
provider_slug: ventrilo
slug: ventrilo-eligibility
source_date: '2026-11-10'
source_filename: ventrilo-eligibility.yml
source_heading: Eligibility
source_page: https://ventrilo.ai/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ventrilo.ai\naid: ventrilo\nurl: https://ventrilo.ai/acceptable-use-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://ventrilo.ai/acceptable-use-policy\n  - https://ventrilo.ai/terms-of-use\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n  source: https://ventrilo.ai/terms-of-use\nrestricted_uses:\n- summary: Election interference and surveillance\n  text: 'engage in surveillance: tracking, targeting or reporting on identity, facial recognition, covert tracking,\n\
  \    battlefield management, predictive policing'\n- summary: Automated high-risk decisions\n  text: make automated decisions in high-risk areas (e.g., employment, credit, housing, insurance) without appropriate\n    human oversight and safeguards\n- summary: Social scoring\n  text: assign social/behavioral “scores” to individuals (social scoring) without consent\n- summary: Hazardous applications\n  text: any use that is sensitive, critical, unsafe, high-risk, or hazardous\n- summary: Acceptable use restrictions on Input\n  text: You represent, warrant, and agree that you will comply with the terms in our Acceptable Use Policy\n  source: https://ventrilo.ai/terms-of-use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 18 years\n    of age; if you are a child under 18 years of age, please do not attempt to register for or\
  \ otherwise use the\n    Services\n  source: https://ventrilo.ai/terms-of-use\n"
source_yaml_url: https://artifacts.apis.io/ventrilo/eligibility/ventrilo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Ventrilo.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Assistant
- Browser Extension
- Productivity
- Writing
- Chrome Extension
- San Francisco
---
