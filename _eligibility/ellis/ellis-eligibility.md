---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal or internal business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to enter into these Terms.
    value: '18'
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
name: Ellis
provenance_date: '2026-11-09'
provider_name: Ellis
provider_slug: ellis
slug: ellis-eligibility
source_date: '2026-11-09'
source_filename: ellis-eligibility.yml
source_heading: Eligibility
source_page: https://www.ellis.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ellis\naid: ellis\nurl: https://www.ellis.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for your personal or internal business purposes\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/ellis/eligibility/ellis-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Ellis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Immigration
- Legal Tech
- Visa
- Green Cards
- Human Resources
- Compliance
- Software-as-a-Service
---
