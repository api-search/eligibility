---
api_specs:
- filename: instacart-authentication-api-openapi.yml
  format: yaml
  label: instacart Authentication API
  slug: instacart-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-authentication-api-openapi.yml
- filename: instacart-chat-api-openapi.yml
  format: yaml
  label: instacart Chat API
  slug: instacart-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-chat-api-openapi.yml
- filename: instacart-delivery-api-openapi.yml
  format: yaml
  label: instacart Delivery API
  slug: instacart-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-delivery-api-openapi.yml
- filename: instacart-items-api-openapi.yml
  format: yaml
  label: instacart Items API
  slug: instacart-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-items-api-openapi.yml
- filename: instacart-last-mile-delivery-api-openapi.yml
  format: yaml
  label: instacart Last Mile Delivery API
  slug: instacart-last-mile-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-last-mile-delivery-api-openapi.yml
- filename: instacart-orders-api-openapi.yml
  format: yaml
  label: instacart Orders API
  slug: instacart-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-orders-api-openapi.yml
- filename: instacart-pickup-api-openapi.yml
  format: yaml
  label: instacart Pickup API
  slug: instacart-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-pickup-api-openapi.yml
- filename: instacart-products-api-openapi.yml
  format: yaml
  label: instacart Products API
  slug: instacart-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-products-api-openapi.yml
- filename: instacart-replacements-api-openapi.yml
  format: yaml
  label: instacart Replacements API
  slug: instacart-replacements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-replacements-api-openapi.yml
- filename: instacart-rest-api-openapi.yml
  format: yaml
  label: instacart Rest API
  slug: instacart-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instacart/openapi/instacart-rest-api-openapi.yml
claim_count: 9
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not a citizen of, or located within, a nation that is subject to U.S. trade sanctions or other significant trade restrictions
  entity_types:
  - text: the individual or entity accessing and using API Materials
    type: individual
  - text: if you are entering into this agreement on behalf of an entity, you have the authority to bind that entity to this Agreement
    type: business
  minimum_age:
    source: https://www.instacart.com/terms
    text: By using the Services, you represent that you are of legal age in the jurisdiction in which you reside to form a binding contract with Instacart.
    value: 18+ or legal age in jurisdiction
  restricted_uses:
  - summary: No medical advice or unsafe conduct
    text: use Instacart Materials or Merchant Content on or with sites/platforms (i) to promote unsafe conduct, (ii) to provide medical advice
  - summary: No migrating users off Instacart
    text: develop an Application whose primary purpose is to migrate end users off of Instacart
  - source: https://www.instacart.com/terms
    summary: Alcohol and age-restricted products
    text: By ordering alcohol, you confirm that both you and the recipient (if different) are of legal drinking age in the delivery location
  - source: https://www.instacart.com/terms
    summary: Resale of prescriptions or restricted products
    text: Prescription Drug Products may not be purchased for resale or for anyone who is not of legal age.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Instacart may require, in its sole discretion, you submit an application to receive access to the data and material hereunder and receive the right to approve or disapprove such application in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Instacart
provenance_date: '2026-11-09'
provider_name: Instacart
provider_slug: instacart
slug: instacart-eligibility
source_date: '2026-11-09'
source_filename: instacart-eligibility.yml
source_heading: Eligibility
source_page: https://docs.instacart.com/developer_platform_api/guide/terms_and_policies/developer_terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instacart\naid: instacart\nurl: https://docs.instacart.com/developer_platform_api/guide/terms_and_policies/developer_terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://docs.instacart.com/developer_platform_api/guide/terms_and_policies/developer_terms\n  - https://www.instacart.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: you are not a citizen of, or located within, a nation that is subject to U.S. trade sanctions or other significant\n    trade restrictions\nentity_types:\n- type: individual\n  text: the individual or entity accessing and using API Materials\n- type: business\n  text: if\
  \ you are entering into this agreement on behalf of an entity, you have the authority to bind that entity\n    to this Agreement\nrestricted_uses:\n- summary: No medical advice or unsafe conduct\n  text: use Instacart Materials or Merchant Content on or with sites/platforms (i) to promote unsafe conduct, (ii)\n    to provide medical advice\n- summary: No migrating users off Instacart\n  text: develop an Application whose primary purpose is to migrate end users off of Instacart\n- summary: Alcohol and age-restricted products\n  text: By ordering alcohol, you confirm that both you and the recipient (if different) are of legal drinking age\n    in the delivery location\n  source: https://www.instacart.com/terms\n- summary: Resale of prescriptions or restricted products\n  text: Prescription Drug Products may not be purchased for resale or for anyone who is not of legal age.\n  source: https://www.instacart.com/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ Instacart may require, in its sole discretion, you submit an application to receive access to the data and\n    material hereunder and receive the right to approve or disapprove such application in its sole discretion.\nminimum_age:\n  value: 18+ or legal age in jurisdiction\n  text: By using the Services, you represent that you are of legal age in the jurisdiction in which you reside to\n    form a binding contract with Instacart.\n  source: https://www.instacart.com/terms\n"
source_yaml_url: https://artifacts.apis.io/instacart/eligibility/instacart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 9 quoted statements, read from Instacart's own page on 2026-11-09.
synthetic: false
tags:
- Grocery
- E-Commerce
- Marketplace
- Retail
- Logistics
- Last Mile Delivery
- Fulfillment
- Catalog
- Advertising
- Agents
- MCP
- Agentic Commerce
---
