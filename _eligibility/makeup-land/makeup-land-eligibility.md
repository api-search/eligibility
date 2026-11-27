---
api_specs:
- filename: makeup-land-brands-api-openapi.yml
  format: yaml
  label: makeup.land Brands API
  slug: makeup-land-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-brands-api-openapi.yml
- filename: makeup-land-cart-api-openapi.yml
  format: yaml
  label: makeup.land Cart API
  slug: makeup-land-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-cart-api-openapi.yml
- filename: makeup-land-customers-api-openapi.yml
  format: yaml
  label: makeup.land Customers API
  slug: makeup-land-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-customers-api-openapi.yml
- filename: makeup-land-gift-cards-api-openapi.yml
  format: yaml
  label: makeup.land Gift Cards API
  slug: makeup-land-gift-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-gift-cards-api-openapi.yml
- filename: makeup-land-orders-api-openapi.yml
  format: yaml
  label: makeup.land Orders API
  slug: makeup-land-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-orders-api-openapi.yml
- filename: makeup-land-payment-links-api-openapi.yml
  format: yaml
  label: makeup.land Payment Links API
  slug: makeup-land-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-payment-links-api-openapi.yml
- filename: makeup-land-products-api-openapi.yml
  format: yaml
  label: makeup.land Products API
  slug: makeup-land-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-products-api-openapi.yml
- filename: makeup-land-proposals-api-openapi.yml
  format: yaml
  label: makeup.land Proposals API
  slug: makeup-land-proposals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-proposals-api-openapi.yml
- filename: makeup-land-register-api-openapi.yml
  format: yaml
  label: makeup.land Register API
  slug: makeup-land-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makeup-land/openapi/makeup-land-register-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IL
    text: בעל תיבת דואר אלקטרוני פעילה וכתובת מגורים/משלוח בישראל.
  entity_types:
  - text: מלאו לו 18 שנים (או שהוא מחזיק באישור מפורש מאפוטרופוס חוקי).
    type: individual
  minimum_age:
    text: מלאו לו 18 שנים (או שהוא מחזיק באישור מפורש מאפוטרופוס חוקי).
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: בעל תעודת זהות ישראלית תקפה או דרכון תקף. בעל כרטיס אשראי תקף שהונפק על ידי אחת מחברות האשראי המוכרות בישראל או בעולם.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: makeup.land
provenance_date: '2026-11-10'
provider_name: makeup.land
provider_slug: makeup-land
slug: makeup-land-eligibility
source_date: '2026-11-10'
source_filename: makeup-land-eligibility.yml
source_heading: Eligibility
source_page: https://makeup.land/%D7%AA%D7%A0%D7%90%D7%99-%D7%A9%D7%99%D7%9E%D7%95%D7%A9
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: makeup.land\naid: makeup-land\nurl: https://makeup.land/%D7%AA%D7%A0%D7%90%D7%99-%D7%A9%D7%99%D7%9E%D7%95%D7%A9\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IL\n  excluded: []\n  text: בעל תיבת דואר אלקטרוני פעילה וכתובת מגורים/משלוח בישראל.\nentity_types:\n- type: individual\n  text: מלאו לו 18 שנים (או שהוא מחזיק באישור מפורש מאפוטרופוס חוקי).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: בעל תעודת זהות ישראלית תקפה או דרכון תקף. בעל כרטיס אשראי תקף שהונפק על ידי אחת מחברות האשראי המוכרות בישראל\n    או בעולם.\nminimum_age:\n  value: '18'\n  text:\
  \ מלאו לו 18 שנים (או שהוא מחזיק באישור מפורש מאפוטרופוס חוקי).\n"
source_yaml_url: https://artifacts.apis.io/makeup-land/eligibility/makeup-land-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from makeup.land's own page on 2026-11-10.
synthetic: false
tags:
- Cosmetics
- Beauty
- Retail
- E-Commerce
- Shopping
- Loyalty
- Gift Cards
- Product Search
- Agentic Commerce
- MCP
- Agent-Native
- Israel
- A2A
---
