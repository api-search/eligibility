---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is intended for use only by persons located in the United States.
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to create an account
    type: individual
  - text: If you create or manage an account for another person, you represent that you have legal authority to do so
    type: other
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to create an account (“User Account”) and use the Platform.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Platform only for lawful purposes and in accordance with these Terms.
  - summary: Not for emergencies
    text: DO NOT USE THE PLATFORM FOR EMERGENCIES OR URGENT SITUATIONS.
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
name: Hazel Health
provenance_date: '2026-11-09'
provider_name: Hazel Health
provider_slug: hazel-health
slug: hazel-health-eligibility
source_date: '2026-11-09'
source_filename: hazel-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.hazel.co/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hazel Health\naid: hazel-health\nurl: https://www.hazel.co/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is intended for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to create an account\n- type: other\n  text: If you create or manage an account for another person, you represent that you have legal authority to do\n    so\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Platform only for\
  \ lawful purposes and in accordance with these Terms.\n- summary: Not for emergencies\n  text: DO NOT USE THE PLATFORM FOR EMERGENCIES OR URGENT SITUATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to create an account (“User\n    Account”) and use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/hazel-health/eligibility/hazel-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Hazel Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Mental Health
- Behavioral Health
- K-12 Education
- Digital Health
- Virtual Care
---
