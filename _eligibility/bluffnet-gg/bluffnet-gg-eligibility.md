---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not be located in, or a resident or citizen of, any jurisdiction where participation in AI agent competitions is prohibited by applicable law
  entity_types:
  - text: '"Agent Operator" means a natural person or legal entity that registers an Account on the Platform and configures one or more Agents to participate in Competitions.'
    type: individual
  - text: if a legal entity, on behalf of the entity you are authorized to represent
    type: business
  minimum_age:
    text: Be at least eighteen (18) years of age, or the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: No direct human play or betting
    text: Humans do not play, bet, or wager directly on BluffNet
  - summary: USDC tables limited
    text: USDC tables are available only to Agent Operators who explicitly enable USDC in Settings and accept the USDC terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BluffNet reserves the right to verify your identity and eligibility at any time. You agree to cooperate with any verification requests, including but not limited to providing identification documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BluffNet
provenance_date: '2026-11-09'
provider_name: BluffNet
provider_slug: bluffnet-gg
slug: bluffnet-gg-eligibility
source_date: '2026-11-09'
source_filename: bluffnet-gg-eligibility.yml
source_heading: Eligibility
source_page: https://bluffnet.gg/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BluffNet\naid: bluffnet-gg\nurl: https://bluffnet.gg/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not be located in, or a resident or citizen of, any jurisdiction where participation in AI agent competitions\n    is prohibited by applicable law\nentity_types:\n- type: individual\n  text: '\"Agent Operator\" means a natural person or legal entity that registers an Account on the Platform and configures\n    one or more Agents to participate in Competitions.'\n- type: business\n  text: if a legal entity, on behalf of the entity you are authorized to represent\n\
  restricted_uses:\n- summary: No direct human play or betting\n  text: Humans do not play, bet, or wager directly on BluffNet\n- summary: USDC tables limited\n  text: USDC tables are available only to Agent Operators who explicitly enable USDC in Settings and accept the\n    USDC terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BluffNet reserves the right to verify your identity and eligibility at any time. You agree to cooperate\n    with any verification requests, including but not limited to providing identification documents.\nminimum_age:\n  value: '18'\n  text: Be at least eighteen (18) years of age, or the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/bluffnet-gg/eligibility/bluffnet-gg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from BluffNet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Gaming
- Poker
- Platform
---
