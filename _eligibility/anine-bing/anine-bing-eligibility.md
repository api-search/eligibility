---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Shipping destination selector lists many countries, but the terms do not themselves limit eligibility by country beyond the statement that sales may be limited to any geographic region.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: Anine Bing reserves the right to require you to prove that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: You may not use our service or products for any illegal or unauthorized purpose
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
name: Anine Bing
provenance_date: '2026-11-09'
provider_name: Anine Bing
provider_slug: anine-bing
slug: anine-bing-eligibility
source_date: '2026-11-09'
source_filename: anine-bing-eligibility.yml
source_heading: Eligibility
source_page: https://www.aninebing.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anine Bing\naid: anine-bing\nurl: https://www.aninebing.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Shipping destination selector lists many countries, but the terms do not themselves limit eligibility by\n    country beyond the statement that sales may be limited to any geographic region.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: You may not use\
  \ our service or products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Anine Bing reserves the right to require you to prove that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/anine-bing/eligibility/anine-bing-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Anine Bing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Fashion
- Apparel
- E-Commerce
- Shopify
- Agentic Commerce
- MCP
---
