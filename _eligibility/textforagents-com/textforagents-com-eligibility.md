---
api_specs:
- filename: textforagents-com-accounts-api-openapi.yml
  format: yaml
  label: textforagents-com Accounts API
  slug: textforagents-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-accounts-api-openapi.yml
- filename: textforagents-com-admin-api-openapi.yml
  format: yaml
  label: textforagents-com Admin API
  slug: textforagents-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-admin-api-openapi.yml
- filename: textforagents-com-auth-api-openapi.yml
  format: yaml
  label: textforagents-com Auth API
  slug: textforagents-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-auth-api-openapi.yml
- filename: textforagents-com-billing-api-openapi.yml
  format: yaml
  label: textforagents-com Billing API
  slug: textforagents-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-billing-api-openapi.yml
- filename: textforagents-com-health-api-openapi.yml
  format: yaml
  label: textforagents-com Health API
  slug: textforagents-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-health-api-openapi.yml
- filename: textforagents-com-legal-api-openapi.yml
  format: yaml
  label: textforagents-com Legal API
  slug: textforagents-com-legal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-legal-api-openapi.yml
- filename: textforagents-com-messages-api-openapi.yml
  format: yaml
  label: textforagents-com Messages API
  slug: textforagents-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-messages-api-openapi.yml
- filename: textforagents-com-support-api-openapi.yml
  format: yaml
  label: textforagents-com Support API
  slug: textforagents-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-support-api-openapi.yml
- filename: textforagents-com-wallet-creation-api-openapi.yml
  format: yaml
  label: textforagents-com Wallet Creation API
  slug: textforagents-com-wallet-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-wallet-creation-api-openapi.yml
- filename: textforagents-com-webhooks-api-openapi.yml
  format: yaml
  label: textforagents-com Webhooks API
  slug: textforagents-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-webhooks-api-openapi.yml
- filename: textforagents-com-x402-api-openapi.yml
  format: yaml
  label: textforagents-com X402 API
  slug: textforagents-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-x402-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: US A2P messaging requires a registered brand and campaign; Canada's CASL is referenced for messages sent to or from recipients in Canada.
  entity_types:
  - text: The account owner must be at least 18 years old (or the age of majority where they live, if higher) and able to form a binding contract.
    type: individual
  minimum_age:
    text: The account owner must be at least 18 years old (or the age of majority where they live, if higher)
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: One verified identity stands behind every messaging brand (see §6). Payment may be pseudonymous; sending identity may not.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TextForAgents
provenance_date: '2026-11-10'
provider_name: TextForAgents
provider_slug: textforagents-com
slug: textforagents-com-eligibility
source_date: '2026-11-10'
source_filename: textforagents-com-eligibility.yml
source_heading: Eligibility
source_page: https://textforagents.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TextForAgents\naid: textforagents-com\nurl: https://textforagents.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: US A2P messaging requires a registered brand and campaign; Canada's CASL is referenced for messages sent\n    to or from recipients in Canada.\nentity_types:\n- type: individual\n  text: The account owner must be at least 18 years old (or the age of majority where they live, if higher) and\n    able to form a binding contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: One verified identity stands\
  \ behind every messaging brand (see §6). Payment may be pseudonymous; sending\n    identity may not.\nminimum_age:\n  value: '18'\n  text: The account owner must be at least 18 years old (or the age of majority where they live, if higher)\n"
source_yaml_url: https://artifacts.apis.io/textforagents-com/eligibility/textforagents-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from TextForAgents's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Telephony
- SMS
- Agents
---
