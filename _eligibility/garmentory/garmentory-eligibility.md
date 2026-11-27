---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: this website and its content are intended for access and use by U.S. residents
  entity_types:
  - text: Our services are available only to, and may only be used by, individuals who are of an age to form a legally binding contract under applicable law.
    type: individual
  minimum_age:
    text: If you are located in the United States, you must be at least 18 years old to use this website.
    value: '18'
  restricted_uses:
  - summary: Prohibited uploaded content
    text: You shall not upload to, distribute, or otherwise publish through the website any content, information or other material (a) that violates, misappropriates or infringes the copyrights, patents, trademarks, service marks, trade secrets, or other proprietary rights of any person or entity
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
name: Garmentory
provenance_date: '2026-11-09'
provider_name: Garmentory
provider_slug: garmentory
slug: garmentory-eligibility
source_date: '2026-11-09'
source_filename: garmentory-eligibility.yml
source_heading: Eligibility
source_page: https://www.garmentory.com/static/terms_and_privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Garmentory\naid: garmentory\nurl: https://www.garmentory.com/static/terms_and_privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: this website and its content are intended for access and use by U.S. residents\nentity_types:\n- type: individual\n  text: Our services are available only to, and may only be used by, individuals who are of an age to form a legally\n    binding contract under applicable law.\nrestricted_uses:\n- summary: Prohibited uploaded content\n  text: You shall not upload to, distribute, or otherwise publish through the website any content, information or\n\
  \    other material (a) that violates, misappropriates or infringes the copyrights, patents, trademarks, service\n    marks, trade secrets, or other proprietary rights of any person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are located in the United States, you must be at least 18 years old to use this website.\n"
source_yaml_url: https://artifacts.apis.io/garmentory/eligibility/garmentory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Garmentory's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fashion
- Marketplace
- E-Commerce
- Retail
- Apparel
- Boutiques
- Shopping
---
