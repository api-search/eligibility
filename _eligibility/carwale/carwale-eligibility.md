---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Used cars listed on CarWale.com for sale may be purchased by individuals for own use only.
    type: individual
  - text: If you are registering as a business entity, you represent that you have the authority to bind the entity to this User Agreement.
    type: business
  minimum_age:
    text: Persons who are "incompetent to contract" within the meaning of the Indian Contract Act, 1872 including minors, un-discharged insolvents etc. are not eligible to use the Site.
    value: null
  restricted_uses:
  - summary: No used car purchases by businesses
    text: These cars may not be purchased by dealers, brokers, or any other business entity
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
name: CarWale
provenance_date: '2026-11-09'
provider_name: CarWale
provider_slug: carwale
slug: carwale-eligibility
source_date: '2026-11-09'
source_filename: carwale-eligibility.yml
source_heading: Eligibility
source_page: https://www.carwale.com/visitor-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarWale\naid: carwale\nurl: https://www.carwale.com/visitor-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Used cars listed on CarWale.com for sale may be purchased by individuals for own use only.\n- type: business\n  text: If you are registering as a business entity, you represent that you have the authority to bind the entity\n    to this User Agreement.\nrestricted_uses:\n- summary: No used car purchases by businesses\n  text: These cars may not be purchased by dealers, brokers, or any other business entity\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Persons who are \"incompetent to contract\" within the meaning of the Indian Contract Act, 1872 including\n    minors, un-discharged insolvents etc. are not eligible to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/carwale/eligibility/carwale-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CarWale's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Cars
- India
- Used Cars
- New Cars
- E-Commerce
---
