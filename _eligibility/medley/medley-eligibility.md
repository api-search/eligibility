---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We are based in the United States. We make no claims that the Service or any of its content is accessible or appropriate outside of the United States.
  minimum_age:
    text: You must be at least eighteen (18) years old to become a Member.
    value: '18'
  restricted_uses:
  - summary: No medical, legal or professional advice
    text: Medley is not engaged in rendering medical, legal or professional advice or services via the Service.
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
name: Medley
provenance_date: '2026-11-10'
provider_name: Medley
provider_slug: medley
slug: medley-eligibility
source_date: '2026-11-10'
source_filename: medley-eligibility.yml
source_heading: Eligibility
source_page: https://www.withmedley.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medley\naid: medley\nurl: https://www.withmedley.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We are based in the United States. We make no claims that the Service or any of its content is accessible\n    or appropriate outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: No medical, legal or professional advice\n  text: Medley is not engaged in rendering medical, legal or professional advice or services via the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least eighteen (18) years old to become a Member.\n"
source_yaml_url: https://artifacts.apis.io/medley/eligibility/medley-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Medley's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Leadership Development
- Coaching
- Enterprise
- Human Resources
- Professional Development
- Learning
---
