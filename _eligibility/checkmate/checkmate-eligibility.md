---
api_specs:
- filename: checkmate-health-api-openapi.yml
  format: yaml
  label: Checkmate Health API
  slug: checkmate-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmate/openapi/checkmate-health-api-openapi.yml
- filename: checkmate-merchants-api-openapi.yml
  format: yaml
  label: Checkmate Merchants API
  slug: checkmate-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmate/openapi/checkmate-merchants-api-openapi.yml
- filename: checkmate-shoppers-api-openapi.yml
  format: yaml
  label: Checkmate Shoppers API
  slug: checkmate-shoppers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmate/openapi/checkmate-shoppers-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: You must be an individual and at least 18 years old, or the age of majority in your state, province, or country of residence
    type: individual
  - text: For business users, these Terms and Conditions, together with any applicable Insertion Orders and materials referenced herein
    type: business
  minimum_age:
    text: You must be an individual and at least 18 years old, or the age of majority in your state, province, or country of residence
    value: '18'
  restricted_uses:
  - summary: Lawful personal non-commercial use only
    text: You are only entitled to access and use our Site for lawful, personal and non-commercial purposes
  - summary: Competitors barred from accessing services
    text: Competitors are strictly prohibited from creating an account, accessing, using, or otherwise engaging with Checkmate's products and services
  - summary: Site not tailored to HIPAA/FISMA
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Checkmate
provenance_date: '2026-11-09'
provider_name: Checkmate
provider_slug: checkmate
slug: checkmate-eligibility
source_date: '2026-11-09'
source_filename: checkmate-eligibility.yml
source_heading: Eligibility
source_page: https://joincheckmate.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Checkmate\naid: checkmate\nurl: https://joincheckmate.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: You must be an individual and at least 18 years old, or the age of majority in your state, province, or\n    country of residence\n- type: business\n  text: For business users, these Terms and\
  \ Conditions, together with any applicable Insertion Orders and materials\n    referenced herein\nrestricted_uses:\n- summary: Lawful personal non-commercial use only\n  text: You are only entitled to access and use our Site for lawful, personal and non-commercial purposes\n- summary: Competitors barred from accessing services\n  text: Competitors are strictly prohibited from creating an account, accessing, using, or otherwise engaging with\n    Checkmate's products and services\n- summary: Site not tailored to HIPAA/FISMA\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be an individual and at least 18 years old, or\
  \ the age of majority in your state, province, or\n    country of residence\n"
source_yaml_url: https://artifacts.apis.io/checkmate/eligibility/checkmate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Checkmate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Commerce
- E-Commerce
- Shopping
- Discount Codes
- Coupons
- Merchants
- MCP
- Agentic Commerce
- Retail
---
