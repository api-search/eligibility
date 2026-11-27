---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website and Services are directed only to residents of the United States.
  minimum_age:
    text: MINORS UNDER THIRTEEN (13) YEARS OLD ARE NOT PERMITTED TO ACCESS OR USE THE SERVICES, EVEN IF A PARENT OR LEGAL GUARDIAN WOULD BE WILLING TO PROVIDE CONSENT.
    value: '13'
  restricted_uses:
  - summary: No resale of products
    text: Purchase of Products for resale (to other consumers, businesses, or third parties) is strictly prohibited.
  - summary: Not for other medical conditions or emergencies
    text: The Website, Services, and Products are not for any other medical or dermatological conditions, including skin cancer
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
name: Curology
provenance_date: '2026-11-09'
provider_name: Curology
provider_slug: curology
slug: curology-eligibility
source_date: '2026-11-09'
source_filename: curology-eligibility.yml
source_heading: Eligibility
source_page: https://curology.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curology\naid: curology\nurl: https://curology.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website and Services are directed only to residents of the United States.\nentity_types: []\nrestricted_uses:\n- summary: No resale of products\n  text: Purchase of Products for resale (to other consumers, businesses, or third parties) is strictly prohibited.\n- summary: Not for other medical conditions or emergencies\n  text: The Website, Services, and Products are not for any other medical or dermatological conditions, including\n    skin cancer\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: MINORS UNDER THIRTEEN (13) YEARS OLD ARE NOT PERMITTED TO ACCESS OR USE THE SERVICES, EVEN IF A PARENT OR\n    LEGAL GUARDIAN WOULD BE WILLING TO PROVIDE CONSENT.\n"
source_yaml_url: https://artifacts.apis.io/curology/eligibility/curology-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Curology's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Skincare
- Dermatology
- Telehealth
- Subscription
- Consumer
---
