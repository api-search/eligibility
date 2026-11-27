---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not (i) located in, or a resident or national of, any country subject to U.S. government embargo or designated as a “terrorist supporting” country, or (ii) on any U.S. government list of prohibited or restricted parties.
  entity_types:
  - text: If you are entering into these terms on behalf of an entity, you represent and warrant that you have the legal authority to bind that entity to these terms
    type: business
  - text: Certain features of the Services may be accessed without creating an account, subject to usage limitations as displayed on the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk applications
    text: use the Services in connection with any application or system where failure or malfunction could reasonably be expected to lead to death, personal injury, or significant property or environmental damage
  - summary: Sensitive data submission
    text: without our prior written consent or a data processing addendum with us, submit or process through the Services any government-issued identifiers, precise health or biometric data, payment card primary account numbers, bank account numbers, children's data subject to child privacy laws
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
name: Symbolica
provenance_date: '2026-11-10'
provider_name: Symbolica
provider_slug: symbolica
slug: symbolica-eligibility
source_date: '2026-11-10'
source_filename: symbolica-eligibility.yml
source_heading: Eligibility
source_page: https://www.symbolica.ai/terms/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Symbolica\naid: symbolica\nurl: https://www.symbolica.ai/terms/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not (i) located in, or a resident or national of, any country subject\n    to U.S. government embargo or designated as a “terrorist supporting” country, or (ii) on any U.S. government\n    list of prohibited or restricted parties.\nentity_types:\n- type: business\n  text: If you are entering into these terms on behalf of an entity, you represent and warrant that you have the\n    legal authority to bind that entity to these\
  \ terms\n- type: individual\n  text: Certain features of the Services may be accessed without creating an account, subject to usage limitations\n    as displayed on the Services.\nrestricted_uses:\n- summary: High-risk applications\n  text: use the Services in connection with any application or system where failure or malfunction could reasonably\n    be expected to lead to death, personal injury, or significant property or environmental damage\n- summary: Sensitive data submission\n  text: without our prior written consent or a data processing addendum with us, submit or process through the Services\n    any government-issued identifiers, precise health or biometric data, payment card primary account numbers, bank\n    account numbers, children's data subject to child privacy laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/symbolica/eligibility/symbolica-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Symbolica's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- AI Agents
- SDK
- Developer Tools
- LLM
- Machine Learning
---
