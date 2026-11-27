---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (b) are a legal resident of the United States
  entity_types:
  - text: YOU MUST BE A LEGAL ADULT IN THE JURISDICTION WHERE YOU LIVE ( i.e. 18 or over in most U.S. states) TO AGREE TO THESE TERMS.
    type: individual
  - text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized to accept these Terms on such entity’s behalf
    type: business
  minimum_age:
    text: Our Applications are not targeted toward or intended for use by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No commercial activities on Applications
    text: You may not use the Applications to engage in any commercial activities
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
name: Daily Harvest
provenance_date: '2026-11-09'
provider_name: Daily Harvest
provider_slug: daily-harvest
slug: daily-harvest-eligibility
source_date: '2026-11-09'
source_filename: daily-harvest-eligibility.yml
source_heading: Eligibility
source_page: https://daily-harvest.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daily Harvest\naid: daily-harvest\nurl: https://daily-harvest.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (b) are a legal resident of the United States\nentity_types:\n- type: individual\n  text: YOU MUST BE A LEGAL ADULT IN THE JURISDICTION WHERE YOU LIVE ( i.e. 18 or over in most U.S. states) TO AGREE\n    TO THESE TERMS.\n- type: business\n  text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized\n    to accept these Terms on such entity’s behalf\nrestricted_uses:\n\
  - summary: No commercial activities on Applications\n  text: You may not use the Applications to engage in any commercial activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Applications are not targeted toward or intended for use by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/daily-harvest/eligibility/daily-harvest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Daily Harvest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Direct to Consumer
- E-Commerce
- Food Delivery
- Health and Wellness
- Subscription
- Shopify
---
