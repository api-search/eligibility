---
api_specs:
- filename: agentkey-openapi-generated.yml
  format: yaml
  label: AgentKey API
  slug: agentkey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentkey/openapi/_ae-authored/agentkey-openapi-generated.yml
- filename: agentkey-install-api-openapi.yml
  format: yaml
  label: AgentKey (Data API Layer) Install API
  slug: agentkey-install-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentkey/openapi/agentkey-install-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access, use, or pay for the Service from, or on behalf of any person or entity located in or ordinarily resident in, any country or territory subject to comprehensive economic sanctions or trade embargoes
  entity_types:
  - text: any individual or entity accessing or using the Service
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No crypto, securities or regulated financial services
    text: Use the Service to buy, sell, exchange, custody, transfer, or otherwise trade cryptocurrencies, digital assets, or securities, or to provide regulated financial, money-transmission, or payment services
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
name: AgentKey (Data API Layer)
provenance_date: '2026-11-09'
provider_name: AgentKey (Data API Layer)
provider_slug: agentkey
slug: agentkey-eligibility
source_date: '2026-11-09'
source_filename: agentkey-eligibility.yml
source_heading: Eligibility
source_page: https://agentkey.app/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentKey (Data API Layer)\naid: agentkey\nurl: https://agentkey.app/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access, use, or pay for the Service from, or on behalf of any person or entity located in or ordinarily\n    resident in, any country or territory subject to comprehensive economic sanctions or trade embargoes\nentity_types:\n- type: individual\n  text: any individual or entity accessing or using the Service\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization\
  \ to these Terms.\nrestricted_uses:\n- summary: No crypto, securities or regulated financial services\n  text: Use the Service to buy, sell, exchange, custody, transfer, or otherwise trade cryptocurrencies, digital\n    assets, or securities, or to provide regulated financial, money-transmission, or payment services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentkey/eligibility/agentkey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AgentKey (Data API Layer)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Integration
- Artificial Intelligence
- Automation
---
