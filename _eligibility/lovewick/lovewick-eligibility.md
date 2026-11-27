---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Service for use only by persons located in the United States.
  entity_types:
  - text: this Service is offered and available to users who are 18 years of age or older
    type: individual
  minimum_age:
    text: this Service is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful purpose
    text: Use our Services for any illegal or harmful purpose
  - summary: Impersonation
    text: Create an account in another real person’s or entity’s name, use another’s account, or impersonate another person or entity
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
name: Lovewick
provenance_date: '2026-11-09'
provider_name: Lovewick
provider_slug: lovewick
slug: lovewick-eligibility
source_date: '2026-11-09'
source_filename: lovewick-eligibility.yml
source_heading: Eligibility
source_page: https://lovewick.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lovewick\naid: lovewick\nurl: https://lovewick.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Service for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: this Service is offered and available to users who are 18 years of age or older\nrestricted_uses:\n- summary: Illegal or harmful purpose\n  text: Use our Services for any illegal or harmful purpose\n- summary: Impersonation\n  text: Create an account in another real person’s or entity’s name, use another’s account, or impersonate another\n\
  \    person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: this Service is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/lovewick/eligibility/lovewick-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Lovewick's own page on 2026-11-09.
synthetic: false
tags:
- Relationship
- App
- Couples
- Dating
- Wellness
---
