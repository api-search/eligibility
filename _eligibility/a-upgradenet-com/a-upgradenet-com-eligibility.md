---
api_specs:
- filename: a-upgradenet-com.json
  format: json
  label: a-un API
  slug: a-un-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com.json
- filename: a-upgradenet-com-agent-account-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Agent account API
  slug: a-upgradenet-com-agent-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-agent-account-api-openapi.yml
- filename: a-upgradenet-com-agent-identity-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Agent identity API
  slug: a-upgradenet-com-agent-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-agent-identity-api-openapi.yml
- filename: a-upgradenet-com-authenticated-products-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Authenticated products API
  slug: a-upgradenet-com-authenticated-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-authenticated-products-api-openapi.yml
- filename: a-upgradenet-com-discovery-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Discovery API
  slug: a-upgradenet-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-discovery-api-openapi.yml
- filename: a-upgradenet-com-evolution-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Evolution API
  slug: a-upgradenet-com-evolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-evolution-api-openapi.yml
- filename: a-upgradenet-com-marketplace-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Marketplace API
  slug: a-upgradenet-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-marketplace-api-openapi.yml
- filename: a-upgradenet-com-mcp-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network MCP API
  slug: a-upgradenet-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-mcp-api-openapi.yml
- filename: a-upgradenet-com-pay-per-call-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Pay per call API
  slug: a-upgradenet-com-pay-per-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-pay-per-call-api-openapi.yml
- filename: a-upgradenet-com-upgrades-api-openapi.yml
  format: yaml
  label: Agent Upgrade Network Upgrades API
  slug: a-upgradenet-com-upgrades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/a-upgradenet-com/openapi/a-upgradenet-com-upgrades-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page does not list served or excluded countries; it mentions compliance with sanctions and export-control laws.
  entity_types:
  - text: a-un is intended for adults and organizations able to enter into legally binding agreements. You must be at least 18 years old, or the higher age of legal majority required where you live.
    type: individual
  - text: If you use a-un for a company or other entity, you represent that you have authority to bind that entity and to configure Agents acting for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the higher age of legal majority required where you live.
    value: '18'
  restricted_uses:
  - summary: Sanctions/legal restrictions
    text: a-un may restrict access or transactions where required to comply with applicable sanctions, anti-fraud or legal obligations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: a-un may require email confirmation, multi-factor authentication, signed challenges or other safeguards for sensitive operations.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agent Upgrade Network
provenance_date: '2026-11-09'
provider_name: Agent Upgrade Network
provider_slug: a-upgradenet-com
slug: a-upgradenet-com-eligibility
source_date: '2026-11-09'
source_filename: a-upgradenet-com-eligibility.yml
source_heading: Eligibility
source_page: https://a-upgradenet.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Upgrade Network\naid: a-upgradenet-com\nurl: https://a-upgradenet.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page does not list served or excluded countries; it mentions compliance with sanctions and export-control\n    laws.\nentity_types:\n- type: individual\n  text: a-un is intended for adults and organizations able to enter into legally binding agreements. You must be\n    at least 18 years old, or the higher age of legal majority required where you live.\n- type: business\n  text: If you use a-un for a company or other entity, you represent that\
  \ you have authority to bind that entity\n    and to configure Agents acting for it.\nrestricted_uses:\n- summary: Sanctions/legal restrictions\n  text: a-un may restrict access or transactions where required to comply with applicable sanctions, anti-fraud\n    or legal obligations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: a-un may require email confirmation, multi-factor authentication, signed challenges or other safeguards\n    for sensitive operations.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the higher age of legal majority required where you live.\n"
source_yaml_url: https://artifacts.apis.io/a-upgradenet-com/eligibility/a-upgradenet-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Agent Upgrade Network's own page on 2026-11-09.
synthetic: false
tags:
- AI Agent Upgrades
- USDC Payments
---
