---
api_specs:
- filename: bookkeep-com-entities-api-openapi.yml
  format: yaml
  label: Bookkeep.com Entities API
  slug: bookkeep-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookkeep-com/openapi/bookkeep-com-entities-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access or use the Service from outside of the United States, you do so at your own risk.
  entity_types:
  - text: the Service is solely for use in the internal operations of your own business
    type: business
  - text: You may be required to register with Bookkeep or provide information about yourself
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: No employee, independent contractor, agent, or affiliate of any competing automated accounting company is permitted to view, access, or use any portion of the Service without express written permission from Bookkeep.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to accept or refuse Subscribers in our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bookkeep.com
provenance_date: '2026-11-09'
provider_name: Bookkeep.com
provider_slug: bookkeep-com
slug: bookkeep-com-eligibility
source_date: '2026-11-09'
source_filename: bookkeep-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bookkeep.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bookkeep.com\naid: bookkeep-com\nurl: https://www.bookkeep.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access or use the Service from outside of the United States, you do so at your own risk.\nentity_types:\n- type: business\n  text: the Service is solely for use in the internal operations of your own business\n- type: individual\n  text: You may be required to register with Bookkeep or provide information about yourself\nrestricted_uses:\n- summary: Competitors barred\n  text: No employee, independent contractor, agent, or affiliate of any competing\
  \ automated accounting company is\n    permitted to view, access, or use any portion of the Service without express written permission from Bookkeep.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to accept or refuse Subscribers in our discretion.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/bookkeep-com/eligibility/bookkeep-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bookkeep.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Automation
- Shopify
- E-Commerce
- Integration
---
