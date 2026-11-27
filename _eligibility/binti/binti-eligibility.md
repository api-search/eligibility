---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided within the Service is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: you are using the Site for your own individual use
    type: individual
  - text: Any use of the Binti Platform by a paying customer or its employees, contractor or third parties that the customer authorizes to assess the Binti Platform is subject to the terms of the current governing contract
    type: business
  minimum_age:
    text: you are over 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Service for any illegal or unauthorized purpose.
  - summary: Creating accounts for others
    text: you agree that you will not create an account for anyone other than yourself
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
name: Binti
provenance_date: '2026-11-09'
provider_name: Binti
provider_slug: binti
slug: binti-eligibility
source_date: '2026-11-09'
source_filename: binti-eligibility.yml
source_heading: Eligibility
source_page: https://binti.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Binti\naid: binti\nurl: https://binti.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided within the Service is not intended for distribution to or use by any person or\n    entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: you are using the Site for your own individual use\n- type: business\n  text: Any use of the Binti Platform by a paying customer or its employees, contractor or third parties that the\n    customer authorizes to assess the Binti\
  \ Platform is subject to the terms of the current governing contract\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Service for any illegal or unauthorized purpose.\n- summary: Creating accounts for others\n  text: you agree that you will not create an account for anyone other than yourself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/binti/eligibility/binti-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Binti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GovTech
- Child Welfare
- Foster Care
- Government
- Case Management
- Social Services
- CCWIS
---
