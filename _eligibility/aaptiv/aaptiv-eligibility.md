---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Aaptiv makes no representation that materials on the Service are appropriate, lawful, or available for use in any locations other than the United States of America.
  entity_types:
  - text: This Terms of Use ( “Terms of Use”) is a binding contract between you, an individual user
    type: individual
  minimum_age:
    text: The Service is not for persons under the age of 13 (or under 16 for individuals in the European Union) or for any users previously suspended or removed from the Service by Aaptiv.
    value: '13'
  restricted_uses:
  - summary: Jurisdictions where service is illegal
    text: Access to the Service from jurisdictions where the contents or practices of the Service are illegal, unauthorized, or penalized is strictly prohibited.
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
name: Aaptiv
provenance_date: '2026-11-09'
provider_name: Aaptiv
provider_slug: aaptiv
slug: aaptiv-eligibility
source_date: '2026-11-09'
source_filename: aaptiv-eligibility.yml
source_heading: Eligibility
source_page: https://aaptiv.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aaptiv\naid: aaptiv\nurl: https://aaptiv.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Aaptiv makes no representation that materials on the Service are appropriate, lawful, or available for use\n    in any locations other than the United States of America.\nentity_types:\n- type: individual\n  text: This Terms of Use ( “Terms of Use”) is a binding contract between you, an individual user\nrestricted_uses:\n- summary: Jurisdictions where service is illegal\n  text: Access to the Service from jurisdictions where the contents or practices of the Service are illegal,\
  \ unauthorized,\n    or penalized is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is not for persons under the age of 13 (or under 16 for individuals in the European Union) or\n    for any users previously suspended or removed from the Service by Aaptiv.\n"
source_yaml_url: https://artifacts.apis.io/aaptiv/eligibility/aaptiv-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aaptiv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fitness
- Wellness
- Health
- Mobile
- AI Coaching
---
