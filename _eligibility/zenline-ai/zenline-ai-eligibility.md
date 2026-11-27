---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: The Site is intended solely for use by businesses, their employees, and authorized representatives for legitimate business purposes.
    type: business
  - text: If you are a consumer acting outside of any trade, business, craft, or profession, you are not an intended user of the Site.
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No revenue-generating use without authorization
    text: Use the Site for any revenue-generating endeavor or commercial enterprise not expressly authorized by Zenline in writing.
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
name: Zenline AI
provenance_date: '2026-11-10'
provider_name: Zenline AI
provider_slug: zenline-ai
slug: zenline-ai-eligibility
source_date: '2026-11-10'
source_filename: zenline-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.tryzenline.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zenline AI\naid: zenline-ai\nurl: https://www.tryzenline.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: The Site is intended solely for use by businesses, their employees, and authorized representatives for legitimate\n    business purposes.\n- type: individual\n  text: If you are a consumer acting outside of any\
  \ trade, business, craft, or profession, you are not an intended\n    user of the Site.\nrestricted_uses:\n- summary: No revenue-generating use without authorization\n  text: Use the Site for any revenue-generating endeavor or commercial enterprise not expressly authorized by Zenline\n    in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/zenline-ai/eligibility/zenline-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Zenline AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Artificial Intelligence
- Assortment Intelligence
- Category Management
- Pricing
- Analytics
- E-Commerce
---
