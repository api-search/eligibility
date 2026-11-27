---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Website on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  - text: You may use the Services only if you are capable of forming a binding contract with SWIM and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Nstream
provenance_date: '2026-11-10'
provider_name: Nstream
provider_slug: nstream
slug: nstream-eligibility
source_date: '2026-11-10'
source_filename: nstream-eligibility.yml
source_heading: Eligibility
source_page: https://www.nstream.io/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nstream\naid: nstream\nurl: https://www.nstream.io/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Website on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that company or other legal entity to\n    these Terms.\n- type: individual\n  text: You may use the Services only if you are capable of forming a binding contract with SWIM and are not barred\n    from using the Services under applicable law.\n\
  restricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nstream/eligibility/nstream-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Nstream's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Streaming
- Real-Time
- Event Streaming
- Stateful Services
- Streaming APIs
- Data Connectors
- Open Source
- WebSocket
- SwimOS
---
