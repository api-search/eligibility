---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: which could refer to an individual, an employer, an employee associated with an employer account, or any other authorized user of the Service.
    type: individual
  - text: If you are an employer, we also collect information about your business, payment information and any information you provide about your employees
    type: business
  minimum_age:
    text: The Service and its content are not directed at children under the age of 13.
    value: null
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
name: Percolata
provenance_date: '2026-11-10'
provider_name: Percolata
provider_slug: wixsite-com
slug: wixsite-com-eligibility
source_date: '2026-11-10'
source_filename: wixsite-com-eligibility.yml
source_heading: Eligibility
source_page: https://percolata.wixsite.com/percolata/terms-of-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Percolata\naid: wixsite-com\nurl: https://percolata.wixsite.com/percolata/terms-of-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: which could refer to an individual, an employer, an employee associated with an employer account, or any\n    other authorized user of the Service.\n- type: business\n  text: If you are an employer, we also collect information about your business, payment information and any information\n    you provide about your employees\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: The Service and its content are not directed at children under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/wixsite-com/eligibility/wixsite-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Percolata's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Analytics
- Retail
- Staffing
---
