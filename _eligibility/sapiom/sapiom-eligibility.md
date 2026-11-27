---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not use the Services if you or any beneficial owner, director, officer, agent, or end user is a person or entity on any sanctions list or located, organized, or resident in an embargoed or comprehensively sanctioned jurisdiction.
  entity_types:
  - text: The Services are offered and available only to users who are 18 years of age or older and capable of forming a binding contract.
    type: individual
  - text: if you are accessing or using the Services on behalf of an entity, that you have the authority to bind that entity to these Terms of Use.
    type: business
  minimum_age:
    text: The Services are offered and available only to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal transactions and high-risk activities
    text: to engage in, facilitate, or enable illegal transactions or high-risk activities, including transactions involving sanctions targets, ransomware, illicit substances, fraud, and gambling where prohibited
  - summary: Agents misrepresenting automated status
    text: to deploy or operate agents that self-identify as human, or that fail to disclose they are automated when interacting with third parties
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
name: Sapiom
provenance_date: '2026-11-10'
provider_name: Sapiom
provider_slug: sapiom
slug: sapiom-eligibility
source_date: '2026-11-10'
source_filename: sapiom-eligibility.yml
source_heading: Eligibility
source_page: https://docs.sapiom.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sapiom\naid: sapiom\nurl: https://docs.sapiom.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not use the Services if you or any beneficial owner, director, officer, agent, or end user is a\n    person or entity on any sanctions list or located, organized, or resident in an embargoed or comprehensively\n    sanctioned jurisdiction.\nentity_types:\n- type: individual\n  text: The Services are offered and available only to users who are 18 years of age or older and capable of forming\n    a binding contract.\n- type: business\n  text: if you are accessing or\
  \ using the Services on behalf of an entity, that you have the authority to bind that\n    entity to these Terms of Use.\nrestricted_uses:\n- summary: Illegal transactions and high-risk activities\n  text: to engage in, facilitate, or enable illegal transactions or high-risk activities, including transactions\n    involving sanctions targets, ransomware, illicit substances, fraud, and gambling where prohibited\n- summary: Agents misrepresenting automated status\n  text: to deploy or operate agents that self-identify as human, or that fail to disclose they are automated when\n    interacting with third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available only to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/sapiom/eligibility/sapiom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Sapiom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Infrastructure
- MCP
- API Gateway
- Payments
- Agentic Commerce
- Developer Tools
- SDK
---
