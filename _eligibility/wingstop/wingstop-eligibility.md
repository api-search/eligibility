---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The service is available only in the United States.
  entity_types:
  - text: You must be at least 18 years of age or older to use the Services
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or older to use the Services
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
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
name: Wingstop
provenance_date: '2026-11-10'
provider_name: Wingstop
provider_slug: wingstop
slug: wingstop-eligibility
source_date: '2026-11-10'
source_filename: wingstop-eligibility.yml
source_heading: Eligibility
source_page: https://www.wingstop.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wingstop\naid: wingstop\nurl: https://www.wingstop.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The service is available only in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or older to use the Services\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or older to use the Services\n"
source_yaml_url: https://artifacts.apis.io/wingstop/eligibility/wingstop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Wingstop's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Quick Service Restaurant
- Fast Food
- Online Ordering
- Mobile Ordering
- Loyalty
- Delivery
---
