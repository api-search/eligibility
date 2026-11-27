---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Most Merchant locations in the United States accept the Merchant App.
  entity_types:
  - text: The Merchant App is for your personal use only and should not be used for business purposes.
    type: individual
  minimum_age:
    text: The Merchant App is not targeted towards, nor intended for use by, anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No business use
    text: The Merchant App is for your personal use only and should not be used for business purposes.
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
name: Compasscoffee
provenance_date: '2026-11-09'
provider_name: Compasscoffee
provider_slug: compasscoffee
slug: compasscoffee-eligibility
source_date: '2026-11-09'
source_filename: compasscoffee-eligibility.yml
source_heading: Eligibility
source_page: https://www.compasscoffee.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compasscoffee\naid: compasscoffee\nurl: https://www.compasscoffee.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Most Merchant locations in the United States accept the Merchant App.\nentity_types:\n- type: individual\n  text: The Merchant App is for your personal use only and should not be used for business purposes.\nrestricted_uses:\n- summary: No business use\n  text: The Merchant App is for your personal use only and should not be used for business purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: The Merchant App is not targeted towards, nor intended for use by, anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/compasscoffee/eligibility/compasscoffee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Compasscoffee's own page on 2026-11-09.
synthetic: false
tags:
- Coffee
- Specialty
- Retail
- Subscription
- WashingtonDC
---
