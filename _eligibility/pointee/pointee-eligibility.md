---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a legal entity or an individual of legal age to form a binding contract, however, at least 15 years of age (if not, you warrant and affirm that you are using our Services under the supervision of a parent or guardian)
    type: individual
  - text: a legal entity or an individual of legal age to form a binding contract
    type: business
  minimum_age:
    text: at least 15 years of age (if not, you warrant and affirm that you are using our Services under the supervision of a parent or guardian)
    value: '15'
  restricted_uses:
  - summary: Illegal activity
    text: Use Pointee's Platform, Website and/or Services to pursue any illegal activities as defined by the law of any applicable jurisdiction;
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
name: Pointee
provenance_date: '2026-11-10'
provider_name: Pointee
provider_slug: pointee
slug: pointee-eligibility
source_date: '2026-11-10'
source_filename: pointee-eligibility.yml
source_heading: Eligibility
source_page: https://www.pointee.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pointee\naid: pointee\nurl: https://www.pointee.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a legal entity or an individual of legal age to form a binding contract, however, at least 15 years of age\n    (if not, you warrant and affirm that you are using our Services under the supervision of a parent or guardian)\n- type: business\n  text: a legal entity or an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Illegal activity\n  text: Use Pointee's Platform, Website and/or Services to pursue\
  \ any illegal activities as defined by the law of\n    any applicable jurisdiction;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '15'\n  text: at least 15 years of age (if not, you warrant and affirm that you are using our Services under the supervision\n    of a parent or guardian)\n"
source_yaml_url: https://artifacts.apis.io/pointee/eligibility/pointee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pointee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Business Process Automation
- RPA
- Agentic Automation
- AI Agents
- Workflow Automation
- Process Discovery
---
