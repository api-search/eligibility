---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Check the FAQs page of the Website to see where we ship - we don't yet ship to all 50 states but add new states frequently.
  entity_types:
  - text: Only individual people are eligible to participate in Misfits Market's referral program. Businesses may not use referral codes for affiliate lead generation.
    type: individual
  minimum_age:
    text: BY PLACING ANY ORDER FOR ALCOHOLIC BEVERAGES, YOU REPRESENT, WARRANT, AND CERTIFY THAT YOU AND THE RECIPIENT (IF APPLICABLE) OF ANY ALCOHOLIC BEVERAGES ARE AT LEAST 21 YEARS OF AGE.
    value: '21'
  restricted_uses:
  - summary: Alcohol shipping restrictions
    text: 'Alcoholic Beverages cannot be shipped to the following states: Alabama, Alaska, Arkansas, Delaware, Hawaii, Kentucky, Mississippi, Rhode Island, South Dakota, and Utah.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register for a user account before you are able to access certain areas of the Website or order Products
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Imperfect Foods
provenance_date: '2026-11-09'
provider_name: Imperfect Foods
provider_slug: imperfectfoods
slug: imperfectfoods-eligibility
source_date: '2026-11-09'
source_filename: imperfectfoods-eligibility.yml
source_heading: Eligibility
source_page: https://www.imperfectfoods.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imperfect Foods\naid: imperfectfoods\nurl: https://www.imperfectfoods.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Check the FAQs page of the Website to see where we ship - we don't yet ship to all 50 states but add new\n    states frequently.\nentity_types:\n- type: individual\n  text: Only individual people are eligible to participate in Misfits Market's referral program. Businesses may\n    not use referral codes for affiliate lead generation.\nrestricted_uses:\n- summary: Alcohol shipping restrictions\n  text: 'Alcoholic Beverages\
  \ cannot be shipped to the following states: Alabama, Alaska, Arkansas, Delaware, Hawaii,\n    Kentucky, Mississippi, Rhode Island, South Dakota, and Utah.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register for a user account before you are able to access certain areas of the Website or order\n    Products\nminimum_age:\n  value: '21'\n  text: BY PLACING ANY ORDER FOR ALCOHOLIC BEVERAGES, YOU REPRESENT, WARRANT, AND CERTIFY THAT YOU AND THE RECIPIENT\n    (IF APPLICABLE) OF ANY ALCOHOLIC BEVERAGES ARE AT LEAST 21 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/imperfectfoods/eligibility/imperfectfoods-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Imperfect Foods's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grocery
- Food Delivery
- Sustainability
- Food Waste
- E-Commerce
- Consumer
---
