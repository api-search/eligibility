---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products may not be returned from outside the United States or Canada.
  entity_types:
  - text: If you are using the Site on behalf of a company, entity, or organization (collectively “Organization”), then you represent and warrant that you (a) are an authorized representative of that Organization
    type: business
  minimum_age:
    text: No part of the Site is directed to persons under the age of 13.
    value: '13'
  restricted_uses:
  - summary: No automated data gathering
    text: use any data mining, bots, spiders, automated tools or similar data gathering and extraction methods on the contents of the Site
  - summary: No reselling or transfer of site rights
    text: Sell, transfer, or assign any of your rights to use the Site to a third-party without our express written consent;
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
name: Jinx
provenance_date: '2026-11-09'
provider_name: Jinx
provider_slug: jinx
slug: jinx-eligibility
source_date: '2026-11-09'
source_filename: jinx-eligibility.yml
source_heading: Eligibility
source_page: https://www.thinkjinx.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jinx\naid: jinx\nurl: https://www.thinkjinx.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Products may not be returned from outside the United States or Canada.\nentity_types:\n- type: business\n  text: If you are using the Site on behalf of a company, entity, or organization (collectively “Organization”),\n    then you represent and warrant that you (a) are an authorized representative of that Organization\nrestricted_uses:\n- summary: No automated data gathering\n  text: use any data mining, bots, spiders, automated tools or similar data gathering and extraction\
  \ methods on\n    the contents of the Site\n- summary: No reselling or transfer of site rights\n  text: Sell, transfer, or assign any of your rights to use the Site to a third-party without our express written\n    consent;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: No part of the Site is directed to persons under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/jinx/eligibility/jinx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Jinx's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Pet Food
- Pet Nutrition
- E-Commerce
- Direct to Consumer
- Dogs
- Cats
- Shopify
---
