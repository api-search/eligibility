---
api_specs:
- filename: 99-counties-openapi-generated.yml
  format: yaml
  label: 99 Counties API
  slug: 99-counties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/99-counties/openapi/_ae-authored/99-counties-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority in state or province of residence
  restricted_uses:
  - summary: Illegal or harmful use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: 99 Counties
provenance_date: '2026-11-09'
provider_name: 99 Counties
provider_slug: 99-counties
slug: 99-counties-eligibility
source_date: '2026-11-09'
source_filename: 99-counties-eligibility.yml
source_heading: Eligibility
source_page: https://99counties.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 99 Counties\naid: 99-counties\nurl: https://99counties.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products to any person, geographic\n    region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state or province of residence\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/99-counties/eligibility/99-counties-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 99 Counties's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Agentic Commerce
- Regenerative Agriculture
- Food and Beverage
- Shopify
- MCP
- Universal Commerce Protocol
---
