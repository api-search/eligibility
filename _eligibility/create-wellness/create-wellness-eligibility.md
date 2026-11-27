---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least 18, or that you are 18 and you have given us your consent to allow any of your minor dependents over the age of 13 to use this site.
    type: individual
  - text: If you are entering into these Terms on behalf of an entity, you represent that you have the authority to bind such entity.
    type: business
  minimum_age:
    text: By agreeing to these Terms of Service, you represent that you are at least 18
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You may not use our products for any illegal or unauthorized purpose nor may you, in the use of the Service, violate any laws in your jurisdiction
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
name: Create Wellness
provenance_date: '2026-11-09'
provider_name: Create Wellness
provider_slug: create-wellness
slug: create-wellness-eligibility
source_date: '2026-11-09'
source_filename: create-wellness-eligibility.yml
source_heading: Eligibility
source_page: https://trycreate.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Create Wellness\naid: create-wellness\nurl: https://trycreate.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least 18, or that you are 18 and you have given us your consent to allow any\n    of your minor dependents over the age of 13 to use this site.\n- type: business\n  text: If you are entering into these Terms on behalf of an entity, you represent that you have the authority to\n    bind such entity.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You may not\
  \ use our products for any illegal or unauthorized purpose nor may you, in the use of the Service,\n    violate any laws in your jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By agreeing to these Terms of Service, you represent that you are at least 18\n"
source_yaml_url: https://artifacts.apis.io/create-wellness/eligibility/create-wellness-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Create Wellness's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health and Wellness
- Supplements
- Consumer Products
- E-Commerce
- Direct to Consumer
- Agentic Commerce
- MCP
- Shopify
- Nutrition
---
