---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Side
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Licensed agents only
    text: You represent and warrant that, when you register with the Services as an Agent, you are a licensed real estate agent or otherwise authorized to act in such a capacity in the jurisdiction in which you intend to market and offer your services.
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
name: Side
provenance_date: '2026-11-10'
provider_name: Side
provider_slug: sideinc-com
slug: sideinc-com-eligibility
source_date: '2026-11-10'
source_filename: sideinc-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.side.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Side\naid: sideinc-com\nurl: https://www.side.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Side\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer)\
  \ or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\nrestricted_uses:\n- summary: Licensed agents only\n  text: You represent and warrant that, when you register with the Services as an Agent, you are a licensed real\n    estate agent or otherwise authorized to act in such a capacity in the jurisdiction in which you intend to market\n    and offer your services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/sideinc-com/eligibility/sideinc-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Side's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate Brokerage
- Platform
- Agents
- Independent Brokers
- Technology
- Growth
- Productivity
- Community
---
