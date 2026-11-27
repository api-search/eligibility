---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  - text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Fully automated decisions
    text: is for fully automated decision making that adversely impacts an individual’s legal rights or otherwise creates or modifies a binding, enforceable obligation
  - summary: Medical advice
    text: provides medical advice and medical results interpretation
  - summary: Law enforcement or immigration use
    text: generates or disseminates information to be used for administration of justice, law enforcement, immigration or asylum processes
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
name: Generally Intelligent
provenance_date: '2026-11-09'
provider_name: Generally Intelligent
provider_slug: generally-intelligent
slug: generally-intelligent-eligibility
source_date: '2026-11-09'
source_filename: generally-intelligent-eligibility.yml
source_heading: Eligibility
source_page: https://imbue.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Generally Intelligent\naid: generally-intelligent\nurl: https://imbue.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your\
  \ territory)\nrestricted_uses:\n- summary: Fully automated decisions\n  text: is for fully automated decision making that adversely impacts an individual’s legal rights or otherwise\n    creates or modifies a binding, enforceable obligation\n- summary: Medical advice\n  text: provides medical advice and medical results interpretation\n- summary: Law enforcement or immigration use\n  text: generates or disseminates information to be used for administration of justice, law enforcement, immigration\n    or asylum processes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/generally-intelligent/eligibility/generally-intelligent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Generally Intelligent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Research
- Foundation Models
- Agents
- Reasoning
- Reinforcement Learning
- Open Source
---
