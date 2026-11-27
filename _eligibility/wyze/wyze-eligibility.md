---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing the Site from territories where its contents are illegal or unlawful is prohibited. Not all Products and Services are available in Canada or Mexico.
  entity_types:
  - text: You must be at least 16 years of age to access, purchase, or use any of our Products or Services.
    type: individual
  - text: If you use our Products or Services on behalf of another person or entity, (i) all references to “you” throughout these Terms will include that person or entity
    type: business
  minimum_age:
    text: You must be at least 16 years of age to access, purchase, or use any of our Products or Services.
    value: '16'
  restricted_uses:
  - summary: Life safety or emergency use
    text: THE WYZE PRODUCTS AND SERVICES ARE NOT A MONITORED EMERGENCY NOTIFICATION SYSTEM
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use certain Services and Products, you must sign up for a user account with Wyze
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wyze
provenance_date: '2026-11-10'
provider_name: Wyze
provider_slug: wyze
slug: wyze-eligibility
source_date: '2026-11-10'
source_filename: wyze-eligibility.yml
source_heading: Eligibility
source_page: https://www.wyze.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wyze\naid: wyze\nurl: https://www.wyze.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Accessing the Site from territories where its contents are illegal or unlawful is prohibited. Not all Products\n    and Services are available in Canada or Mexico.\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to access, purchase, or use any of our Products or Services.\n- type: business\n  text: If you use our Products or Services on behalf of another person or entity, (i) all references to “you” throughout\n \
  \   these Terms will include that person or entity\nrestricted_uses:\n- summary: Life safety or emergency use\n  text: THE WYZE PRODUCTS AND SERVICES ARE NOT A MONITORED EMERGENCY NOTIFICATION SYSTEM\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use certain Services and Products, you must sign up for a user account with Wyze\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to access, purchase, or use any of our Products or Services.\n"
source_yaml_url: https://artifacts.apis.io/wyze/eligibility/wyze-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wyze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Home
- IoT
- Home Security
- Camera
- Consumer Electronics
- Home Automation
- Video
- Sensors
- Commerce
---
