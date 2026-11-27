---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you are at least 18 years old and have the legal capacity to enter into a binding contract.
    type: individual
  - text: If you accept these Terms on behalf of a company or other organisation, you represent and warrant that you have authority to bind that organisation
    type: business
  minimum_age:
    text: You may use the Service only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions or restricted parties
    text: You may not use the Service if you are located in, or are a resident of, a country subject to comprehensive sanctions that would make provision of the Service unlawful, or if you appear on any applicable restricted-party list.
  - source: https://deplion.cc/legal/acceptable-use-policy
    summary: Adult or gambling content
    text: pornographic or sexually explicit material; gambling, betting or real-money gaming services. These are not permitted by default.
  - source: https://deplion.cc/legal/acceptable-use-policy
    summary: Unlicensed regulated goods
    text: unlicensed sale of prescription medicines, controlled substances, weapons, explosives or other regulated goods
  - source: https://deplion.cc/legal/acceptable-use-policy
    summary: Self-harm promotion
    text: content promoting self-harm, suicide or eating disorders
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
name: Deplion
provenance_date: '2026-11-09'
provider_name: Deplion
provider_slug: deplion-cc
slug: deplion-cc-eligibility
source_date: '2026-11-09'
source_filename: deplion-cc-eligibility.yml
source_heading: Eligibility
source_page: https://deplion.cc/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deplion\naid: deplion-cc\nurl: https://deplion.cc/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://deplion.cc/legal/acceptable-use-policy\n  - https://deplion.cc/legal/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you are at least 18 years old and have the legal capacity to enter into\n    a binding contract.\n- type: business\n  text: If you accept these Terms on behalf of a company or other organisation, you represent and warrant that you\n    have authority to bind that organisation\n\
  restricted_uses:\n- summary: Sanctioned jurisdictions or restricted parties\n  text: You may not use the Service if you are located in, or are a resident of, a country subject to comprehensive\n    sanctions that would make provision of the Service unlawful, or if you appear on any applicable restricted-party\n    list.\n- summary: Adult or gambling content\n  text: pornographic or sexually explicit material; gambling, betting or real-money gaming services. These are not\n    permitted by default.\n  source: https://deplion.cc/legal/acceptable-use-policy\n- summary: Unlicensed regulated goods\n  text: unlicensed sale of prescription medicines, controlled substances, weapons, explosives or other regulated\n    goods\n  source: https://deplion.cc/legal/acceptable-use-policy\n- summary: Self-harm promotion\n  text: content promoting self-harm, suicide or eating disorders\n  source: https://deplion.cc/legal/acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Service only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/deplion-cc/eligibility/deplion-cc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Deplion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Website Publishing
- Web Hosting
- Deployment
- No-Code
- AI Agents
---
