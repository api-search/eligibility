---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company Properties can be accessed from countries around the world and may contain references to Services and Content that are not available in your country.
  entity_types:
  - text: you are (x) at least thirteen (13) years old; (y) of legal age to form a binding contract; and (z) not a person barred from using the Company Properties
    type: individual
  minimum_age:
    text: You represent that you are (x) at least thirteen (13) years old;
    value: '13'
  restricted_uses:
  - summary: School community limited to own school
    text: you are not permitted to join and participate in the App’s online community that pertains to a high school that you do not attend or a college that you do not attend or are not committed to attending.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you are a high school or college student at the school whose Saturn community you seek to join or a future student at a college whose Saturn community you seek to join.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Saturn
provenance_date: '2026-11-10'
provider_name: Saturn
provider_slug: saturn
slug: saturn-eligibility
source_date: '2026-11-10'
source_filename: saturn-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinsaturn.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saturn\naid: saturn\nurl: https://www.joinsaturn.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Company Properties can be accessed from countries around the world and may contain references to Services\n    and Content that are not available in your country.\nentity_types:\n- type: individual\n  text: you are (x) at least thirteen (13) years old; (y) of legal age to form a binding contract; and (z) not a\n    person barred from using the Company Properties\nrestricted_uses:\n- summary: School community limited to own school\n  text: you are\
  \ not permitted to join and participate in the App’s online community that pertains to a high school\n    that you do not attend or a college that you do not attend or are not committed to attending.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you are a high school or college student at the school whose Saturn community you seek to join or a future\n    student at a college whose Saturn community you seek to join.\nminimum_age:\n  value: '13'\n  text: You represent that you are (x) at least thirteen (13) years old;\n"
source_yaml_url: https://artifacts.apis.io/saturn/eligibility/saturn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Saturn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Calendar
- Scheduling
- Consumer
- Mobile
- Social
- Education
- Productivity
---
