---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products may not be returned from outside the United States. Return shipping is free within the United States (not including US territories).
  entity_types:
  - text: If you are using a Site or App on behalf of a company, entity, or organization (collectively, “Organization”), then you represent and warrant that you (a) are an authorized representative of that Organization
    type: business
  minimum_age:
    text: None of our Sites or Apps is directed to persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Export-restricted use
    text: will not use the Services for military, nuclear, missile, chemical, or biological weaponry end uses in violation of United States export laws
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
name: Casper
provenance_date: '2026-11-09'
provider_name: Casper
provider_slug: casper
slug: casper-eligibility
source_date: '2026-11-09'
source_filename: casper-eligibility.yml
source_heading: Eligibility
source_page: https://casper.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casper\naid: casper\nurl: https://casper.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Products may not be returned from outside the United States. Return shipping is free within the United States\n    (not including US territories).\nentity_types:\n- type: business\n  text: If you are using a Site or App on behalf of a company, entity, or organization (collectively, “Organization”),\n    then you represent and warrant that you (a) are an authorized representative of that Organization\nrestricted_uses:\n- summary: Export-restricted\
  \ use\n  text: will not use the Services for military, nuclear, missile, chemical, or biological weaponry end uses in violation\n    of United States export laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: None of our Sites or Apps is directed to persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/casper/eligibility/casper-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Casper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Sleep
- Mattresses
- Direct to Consumer
- Agentic Commerce
- Shopify
---
