---
api_specs:
- filename: schema
  format: yaml
  label: Pixc Public API
  slug: pixc-public-api
  spec_type: OpenAPI
  url: https://dashboard.pixc.com/v1/schema
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Creating an account on Pixc allows you to use and access the Site and its services.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you can use the Site only with involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Data mining and robots
    text: any use of data mining, robots, or similar data gathering and extracting tools.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: This personal information will allow us to verify your identity for future use of Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pixc
provenance_date: '2026-11-10'
provider_name: Pixc
provider_slug: pixc
slug: pixc-eligibility
source_date: '2026-11-10'
source_filename: pixc-eligibility.yml
source_heading: Eligibility
source_page: https://pixc.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pixc\naid: pixc\nurl: https://pixc.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Creating an account on Pixc allows you to use and access the Site and its services.\nrestricted_uses:\n- summary: Data mining and robots\n  text: any use of data mining, robots, or similar data gathering and extracting tools.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: This personal information will allow us to verify your identity for future use of Site.\nminimum_age:\n  value: '18'\n  text: If you are under\
  \ 18 years of age, you can use the Site only with involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/pixc/eligibility/pixc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Pixc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shopify
- E-Commerce
- Photo Editing
- Image Optimization
- Image Processing
- Product Photography
- Background Removal
- SEO
- Automation
- Artificial Intelligence
- Webhook
- Digital Asset Management
---
