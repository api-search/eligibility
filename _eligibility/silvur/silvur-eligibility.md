---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Platform is available only to residents of the United States and is not available to and should not be accessed or used by residents of other nations including, but not limited to, the European Economic Area ('EEA').
  entity_types:
  - text: You must be at least 18 years of age or older to sign-up or register for, or install or use, the Platform or Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or older to sign-up or register for, or install or use, the Platform or Services.
    value: '18'
  restricted_uses:
  - summary: Illegal, fraudulent or illicit activity
    text: you will not access or use the Services to engage in any illegal, fraudulent, or other illicit activity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to establish a Payment Method through the Services, you must provide such other information and documents as requested by us to verify your identity and compliance with these Terms
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Silvur
provenance_date: '2026-11-10'
provider_name: Silvur
provider_slug: silvur
slug: silvur-eligibility
source_date: '2026-11-10'
source_filename: silvur-eligibility.yml
source_heading: Eligibility
source_page: https://www.silvur.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silvur\naid: silvur\nurl: https://www.silvur.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Platform is available only to residents of the United States and is not available to and should not\n    be accessed or used by residents of other nations including, but not limited to, the European Economic Area\n    ('EEA').\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or older to sign-up or register for, or install or use, the Platform\n    or Services.\nrestricted_uses:\n- summary: Illegal, fraudulent or illicit activity\n  text:\
  \ you will not access or use the Services to engage in any illegal, fraudulent, or other illicit activity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to establish a Payment Method through the Services, you must provide such other information and\n    documents as requested by us to verify your identity and compliance with these Terms\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or older to sign-up or register for, or install or use, the Platform\n    or Services.\n"
source_yaml_url: https://artifacts.apis.io/silvur/eligibility/silvur-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Silvur's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Retirement
- Financial Wellness
- Credit Union
- Retirement Planning
- Financial Services
- White Label
- Social Security
- Medicare
---
