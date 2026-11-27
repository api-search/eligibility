---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Services is void where prohibited.
  entity_types:
  - text: The Services are intended for users over the age of eighteen (18).
    type: individual
  - text: You may use the Services for your personal use or for internal business purposes in the organization that you represent.
    type: business
  minimum_age:
    text: The Services are intended for users over the age of eighteen (18).
    value: '18'
  restricted_uses:
  - summary: Developing competing or ML models
    text: Use the Services to develop, train, improve, or test competing products, services, or machine learning models;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Company has sole right and discretion to determine whether to accept a Member, and may reject a Member's registration with or without explanation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Freejit
provenance_date: '2026-11-10'
provider_name: Freejit
provider_slug: qualaroo-com
slug: qualaroo-com-eligibility
source_date: '2026-11-10'
source_filename: qualaroo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.proprofs.com/policies/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freejit\naid: qualaroo-com\nurl: https://www.proprofs.com/policies/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Services is void where prohibited.\nentity_types:\n- type: individual\n  text: The Services are intended for users over the age of eighteen (18).\n- type: business\n  text: You may use the Services for your personal use or for internal business purposes in the organization that\n    you represent.\nrestricted_uses:\n- summary: Developing competing or ML models\n  text: Use the Services to develop, train, improve, or test competing\
  \ products, services, or machine learning models;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Company has sole right and discretion to determine whether to accept a Member, and may reject a Member's\n    registration with or without explanation.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users over the age of eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/qualaroo-com/eligibility/qualaroo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Freejit's own page on 2026-11-10.
synthetic: false
tags:
- Feedback
- Surveys
- Marketing
- Customer Experience
- Artificial Intelligence
---
