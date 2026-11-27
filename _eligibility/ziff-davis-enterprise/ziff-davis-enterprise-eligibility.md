---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Promotions are available to individual users of RetailMeNot who are residents of the United States and at least eighteen (18) years of age.
  entity_types:
  - text: Promotions are available to individual users of RetailMeNot who are residents of the United States and at least eighteen (18) years of age.
    type: individual
  - text: Businesses, organizations or other legal entities may not become Members, and are not permitted to use the Services for any purpose
    type: business
  minimum_age:
    text: You must be 13 years of age or older to use the Services outside of the European Union and European Economic Area, and 16 years of age or older in the European Union and European Economic Area.
    value: '13'
  restricted_uses:
  - summary: Commercial use excluded from promotions
    text: Purchases for resale or commercial use are excluded from eligibility.
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
name: Ziff Davis Enterprise
provenance_date: '2026-11-10'
provider_name: Ziff Davis Enterprise
provider_slug: ziff-davis-enterprise
slug: ziff-davis-enterprise-eligibility
source_date: '2026-11-10'
source_filename: ziff-davis-enterprise-eligibility.yml
source_heading: Eligibility
source_page: https://www.ziffdavis.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ziff Davis Enterprise\naid: ziff-davis-enterprise\nurl: https://www.ziffdavis.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Promotions are available to individual users of RetailMeNot who are residents of the United States and at\n    least eighteen (18) years of age.\nentity_types:\n- type: individual\n  text: Promotions are available to individual users of RetailMeNot who are residents of the United States and at\n    least eighteen (18) years of age.\n- type: business\n  text: Businesses, organizations or other legal entities may not\
  \ become Members, and are not permitted to use the\n    Services for any purpose\nrestricted_uses:\n- summary: Commercial use excluded from promotions\n  text: Purchases for resale or commercial use are excluded from eligibility.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to use the Services outside of the European Union and European Economic\n    Area, and 16 years of age or older in the European Union and European Economic Area.\n"
source_yaml_url: https://artifacts.apis.io/ziff-davis-enterprise/eligibility/ziff-davis-enterprise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ziff Davis Enterprise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Media
- Internet
- Publishing
- Cybersecurity
- Marketing Technology
- Technology
- Publicly Traded
---
