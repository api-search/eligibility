---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a consumer resident in the EU or the UK, you have a legal right to cancel within fourteen (14) days after the day on which the subscription was entered into and to receive a refund
  entity_types:
  - text: the person or entity agreeing to these terms (the “Customer,” “you,” or “your”)
    type: individual
  - text: solely for your own personal or internal business use
    type: business
  minimum_age:
    text: you must be at least 13 years old (or the minimum age of digital consent in your jurisdiction, if higher) to create an Account.
    value: '13'
  restricted_uses:
  - summary: Education Accounts non-commercial only
    text: Education Accounts are intended for learning, teaching, and other non-commercial, classroom, or academic use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An Education Account is available free or at a discount to students and educators who verify their eligibility (for example, with a valid academic email address or proof of enrollment or employment at a qualifying institution).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vizcom
provenance_date: '2026-11-10'
provider_name: Vizcom
provider_slug: vizcom
slug: vizcom-eligibility
source_date: '2026-11-10'
source_filename: vizcom-eligibility.yml
source_heading: Eligibility
source_page: https://vizcom.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vizcom\naid: vizcom\nurl: https://vizcom.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a consumer resident in the EU or the UK, you have a legal right to cancel within fourteen (14)\n    days after the day on which the subscription was entered into and to receive a refund\nentity_types:\n- type: individual\n  text: the person or entity agreeing to these terms (the “Customer,” “you,” or “your”)\n- type: business\n  text: solely for your own personal or internal business use\nrestricted_uses:\n- summary: Education Accounts non-commercial only\n\
  \  text: Education Accounts are intended for learning, teaching, and other non-commercial, classroom, or academic\n    use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An Education Account is available free or at a discount to students and educators who verify their eligibility\n    (for example, with a valid academic email address or proof of enrollment or employment at a qualifying institution).\nminimum_age:\n  value: '13'\n  text: you must be at least 13 years old (or the minimum age of digital consent in your jurisdiction, if higher)\n    to create an Account.\n"
source_yaml_url: https://artifacts.apis.io/vizcom/eligibility/vizcom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Vizcom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Design
- Generative AI
- 3D Rendering
- Product Design
- Industrial Design
- Creative Tools
---
