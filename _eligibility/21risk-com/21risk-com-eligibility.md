---
api_specs:
- filename: 21risk-com-openapi-generated.yml
  format: yaml
  label: 21RISK API
  slug: 21risk-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/21risk-com/openapi/_ae-authored/21risk-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you signed up for 21RISK with a corporate email address, the domain name identifies the customer.
    type: business
  minimum_age:
    text: The customer is responsible for ensuring that no minors under 16 will use the software.
    value: '16'
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
name: 21RISK
provenance_date: '2026-11-09'
provider_name: 21RISK
provider_slug: 21risk-com
slug: 21risk-com-eligibility
source_date: '2026-11-09'
source_filename: 21risk-com-eligibility.yml
source_heading: Eligibility
source_page: https://21risk.com/compliance/customer-terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 21RISK\naid: 21risk-com\nurl: https://21risk.com/compliance/customer-terms-of-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you signed up for 21RISK with a corporate email address, the domain name identifies the customer.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The customer is responsible for ensuring that no minors under 16 will use the software.\n"
source_yaml_url: https://artifacts.apis.io/21risk-com/eligibility/21risk-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from 21RISK's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Property Insurance
- Industrial
- Software
- Automation
---
