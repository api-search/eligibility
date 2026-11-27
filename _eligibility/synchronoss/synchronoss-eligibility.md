---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Synchronoss makes no representation that the Service is appropriate or available for use in locations outside the United States, and accessing the Service is prohibited from territories where doing so would be illegal.
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old, whether acting on their own behalf or as an authorized employee or representative of a corporation or other business entity.
    type: individual
  - text: whether acting on their own behalf or as an authorized employee or representative of a corporation or other business entity.
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: Any unauthorized use of the Service, including without limitation, any commercial use (such as, for example, resale to third parties), is expressly prohibited.
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
name: Synchronoss
provenance_date: '2026-11-10'
provider_name: Synchronoss
provider_slug: synchronoss
slug: synchronoss-eligibility
source_date: '2026-11-10'
source_filename: synchronoss-eligibility.yml
source_heading: Eligibility
source_page: https://www.synchronoss.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synchronoss\naid: synchronoss\nurl: https://www.synchronoss.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Synchronoss makes no representation that the Service is appropriate or available for use in locations outside\n    the United States, and accessing the Service is prohibited from territories where doing so would be illegal.\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old, whether acting on their own\n    behalf or as an authorized employee or representative of a corporation or other business\
  \ entity.\n- type: business\n  text: whether acting on their own behalf or as an authorized employee or representative of a corporation or other\n    business entity.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: Any unauthorized use of the Service, including without limitation, any commercial use (such as, for example,\n    resale to third parties), is expressly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/synchronoss/eligibility/synchronoss-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Synchronoss's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Personal Cloud
- Messaging
- Telecommunications
- White Label
- Data Backup
- Carrier Services
---
