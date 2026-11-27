---
api_specs:
- filename: overview
  format: yaml
  label: Zilla Gateway
  slug: zilla-gateway
  spec_type: Postman
  url: https://www.postman.com/aklivity-zilla/workspace/aklivity-zilla-quickstart/overview
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You represent that you are not located in a restricted jurisdiction or listed on any government-maintained restricted party list.
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
name: Aklivity
provenance_date: '2026-11-09'
provider_name: Aklivity
provider_slug: aklivity
slug: aklivity-eligibility
source_date: '2026-11-09'
source_filename: aklivity-eligibility.yml
source_heading: Eligibility
source_page: https://www.aklivity.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aklivity\naid: aklivity\nurl: https://www.aklivity.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of a company or other legal entity, you represent that you have\n    authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Export restrictions\n  text: You represent that you are not located in a restricted jurisdiction or listed on any government-maintained\n    restricted party list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/aklivity/eligibility/aklivity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aklivity's own page on 2026-11-09.
synthetic: false
tags:
- AI Gateway
- API Gateway
- Agent Infrastructure
- Apache Kafka
- AsyncAPI
- Event-Driven
- IoT
- Kafka Proxy
- MCP
- Multi-Protocol
- Open Source
- Real-Time
---
