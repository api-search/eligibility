---
api_specs:
- filename: agentdrives-com-accounts-api-openapi.yml
  format: yaml
  label: agentdrives-com Accounts API
  slug: agentdrives-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-accounts-api-openapi.yml
- filename: agentdrives-com-claims-api-openapi.yml
  format: yaml
  label: agentdrives-com Claims API
  slug: agentdrives-com-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-claims-api-openapi.yml
- filename: agentdrives-com-directory-api-openapi.yml
  format: yaml
  label: agentdrives-com Directory API
  slug: agentdrives-com-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-directory-api-openapi.yml
- filename: agentdrives-com-follows-api-openapi.yml
  format: yaml
  label: agentdrives-com Follows API
  slug: agentdrives-com-follows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-follows-api-openapi.yml
- filename: agentdrives-com-newsletter-api-openapi.yml
  format: yaml
  label: agentdrives-com Newsletter API
  slug: agentdrives-com-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-newsletter-api-openapi.yml
- filename: agentdrives-com-orders-api-openapi.yml
  format: yaml
  label: agentdrives-com Orders API
  slug: agentdrives-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-orders-api-openapi.yml
- filename: agentdrives-com-pay-over-http-402-api-openapi.yml
  format: yaml
  label: agentdrives-com Pay over HTTP 402 API
  slug: agentdrives-com-pay-over-http-402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-pay-over-http-402-api-openapi.yml
- filename: agentdrives-com-support-api-openapi.yml
  format: yaml
  label: agentdrives-com Support API
  slug: agentdrives-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-support-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Prices are in US dollars, and in euros in the EU, Iceland, Liechtenstein and Norway (the same number).
  entity_types:
  - text: If you buy as a person, not for a business, you can cancel within 14 days of your order without giving a reason.
    type: individual
  - text: You can buy as a person or for your business. For a business, add its name and tax ID at checkout.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of certificate badge
    text: Misusing the badge or the words ends the certificate.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An Audit or its renewal of your product needs a verified claim on its domain.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: agentdrives-com
provenance_date: '2026-11-09'
provider_name: agentdrives-com
provider_slug: agentdrives-com
slug: agentdrives-com-eligibility
source_date: '2026-11-09'
source_filename: agentdrives-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentdrives.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agentdrives-com\naid: agentdrives-com\nurl: https://agentdrives.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Prices are in US dollars, and in euros in the EU, Iceland, Liechtenstein and Norway (the same number).\nentity_types:\n- type: individual\n  text: If you buy as a person, not for a business, you can cancel within 14 days of your order without giving a\n    reason.\n- type: business\n  text: You can buy as a person or for your business. For a business, add its name and tax ID at checkout.\nrestricted_uses:\n- summary: Misuse of certificate badge\n  text:\
  \ Misusing the badge or the words ends the certificate.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An Audit or its renewal of your product needs a verified claim on its domain.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentdrives-com/eligibility/agentdrives-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from agentdrives-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Lab
- Software
- Testing
- Data
---
