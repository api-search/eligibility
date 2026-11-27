---
api_specs:
- filename: caper-network-agent-api-openapi.yml
  format: yaml
  label: Caper Agent API
  slug: caper-network-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-agent-api-openapi.yml
- filename: caper-network-blog-api-openapi.yml
  format: yaml
  label: Caper Blog API
  slug: caper-network-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-blog-api-openapi.yml
- filename: caper-network-blog-xml-api-openapi.yml
  format: yaml
  label: Caper Blog.xml API
  slug: caper-network-blog-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-blog-xml-api-openapi.yml
- filename: caper-network-capers-api-openapi.yml
  format: yaml
  label: Caper Capers API
  slug: caper-network-capers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-capers-api-openapi.yml
- filename: caper-network-llms-txt-api-openapi.yml
  format: yaml
  label: Caper Llms.txt API
  slug: caper-network-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-llms-txt-api-openapi.yml
- filename: caper-network-mcp-api-openapi.yml
  format: yaml
  label: Caper MCP API
  slug: caper-network-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-mcp-api-openapi.yml
- filename: caper-network-sitemap-xml-api-openapi.yml
  format: yaml
  label: Caper Sitemap.xml API
  slug: caper-network-sitemap-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-sitemap-xml-api-openapi.yml
- filename: caper-network-well-known-api-openapi.yml
  format: yaml
  label: Caper .well Known API
  slug: caper-network-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-well-known-api-openapi.yml
- filename: caper-network-wiki-api-openapi.yml
  format: yaml
  label: Caper Wiki API
  slug: caper-network-wiki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-wiki-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 and can enter a binding contract
    type: individual
  minimum_age:
    text: you are at least 18 and can enter a binding contract
    value: '18'
  restricted_uses:
  - summary: Sanctions
    text: you are not subject to sanctions, and are not acting for anyone who is, under any applicable sanctions regime
  - summary: Prohibited jurisdictions and unlawful use
    text: you are not using it from a jurisdiction where it is prohibited
  - summary: Money laundering or criminal finance
    text: you are not using Caper to launder money or finance anything criminal
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
name: Caper
provenance_date: '2026-11-09'
provider_name: Caper
provider_slug: caper-network
slug: caper-network-eligibility
source_date: '2026-11-09'
source_filename: caper-network-eligibility.yml
source_heading: Eligibility
source_page: https://caper.network/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caper\naid: caper-network\nurl: https://caper.network/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 and can enter a binding contract\nrestricted_uses:\n- summary: Sanctions\n  text: you are not subject to sanctions, and are not acting for anyone who is, under any applicable sanctions regime\n- summary: Prohibited jurisdictions and unlawful use\n  text: you are not using it from a jurisdiction where it is prohibited\n- summary: Money laundering or criminal finance\n  text: you are not using Caper to launder\
  \ money or finance anything criminal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 and can enter a binding contract\n"
source_yaml_url: https://artifacts.apis.io/caper-network/eligibility/caper-network-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Caper's own page on 2026-11-09.
synthetic: false
tags:
- DAO
- Blockchain
- Fundraising
- Radix
- Decentralized
---
