---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated from the United States, and use from other jurisdictions is at your own risk.
  entity_types:
  - text: The Company Services are intended for personal, non-commercial use unless otherwise expressly authorized.
    type: individual
  - text: Company provides a communication platform designed to support educational access, student success, and related services for institutions, students, and partners.
    type: other
  minimum_age:
    text: You must be at least 13 years old to use the Company Services. If you are under 16, you may only use the Services with parental or guardian consent.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Company Services are intended for personal, non-commercial use unless otherwise expressly authorized.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to access certain features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mainstay
provenance_date: '2026-11-10'
provider_name: Mainstay
provider_slug: mainstay
slug: mainstay-eligibility
source_date: '2026-11-10'
source_filename: mainstay-eligibility.yml
source_heading: Eligibility
source_page: https://mainstay.com/termsofuse/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mainstay\naid: mainstay\nurl: https://mainstay.com/termsofuse/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated from the United States, and use from other jurisdictions is at your own risk.\nentity_types:\n- type: individual\n  text: The Company Services are intended for personal, non-commercial use unless otherwise expressly authorized.\n- type: other\n  text: Company provides a communication platform designed to support educational access, student success, and related\n    services for institutions, students, and partners.\nrestricted_uses:\n- summary:\
  \ Non-commercial use only\n  text: The Company Services are intended for personal, non-commercial use unless otherwise expressly authorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to access certain features.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Company Services. If you are under 16, you may only use the\n    Services with parental or guardian consent.\n"
source_yaml_url: https://artifacts.apis.io/mainstay/eligibility/mainstay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mainstay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Higher Education
- Conversational AI
- Student Engagement
- Chatbots
- Messaging
---
