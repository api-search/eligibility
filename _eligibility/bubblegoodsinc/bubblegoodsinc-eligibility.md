---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Bubble does not permit sales or shipment of goods (“Items”) outside of the United States.
  entity_types:
  - text: Users must be 18 years of age or older to use the Site.
    type: individual
  minimum_age:
    text: Users must be 18 years of age or older to use the Site.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration may be required in order to use the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bubblegoodsinc
provenance_date: '2026-11-09'
provider_name: Bubblegoodsinc
provider_slug: bubblegoodsinc
slug: bubblegoodsinc-eligibility
source_date: '2026-11-09'
source_filename: bubblegoodsinc-eligibility.yml
source_heading: Eligibility
source_page: https://bubblegoods.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bubblegoodsinc\naid: bubblegoodsinc\nurl: https://bubblegoods.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Bubble does not permit sales or shipment of goods (“Items”) outside of the United States.\nentity_types:\n- type: individual\n  text: Users must be 18 years of age or older to use the Site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration may be required in order to use the Site.\nminimum_age:\n  value: '18'\n  text: Users must be 18 years of age or older to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/bubblegoodsinc/eligibility/bubblegoodsinc-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bubblegoodsinc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Food
- E-Commerce
- Health
---
