---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: acting in your capacity as an individual or an employee or other representative of your company or other entity, if applicable
    type: individual
  - text: for independent agencies, the CoverForce Independent Agency Customer Agreement; for other customers, the applicable Master Service Agreement and Order Form
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal spam
    text: You are strictly prohibited from using the Website or any of the Company's Services for illegal spam activities
  - summary: Pay-per-click on trademarked terms
    text: you may not participate in pay-per-click advertising on the Company's trademarked terms
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
name: Coverforce
provenance_date: '2026-11-09'
provider_name: Coverforce
provider_slug: coverforce
slug: coverforce-eligibility
source_date: '2026-11-09'
source_filename: coverforce-eligibility.yml
source_heading: Eligibility
source_page: https://www.coverforce.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coverforce\naid: coverforce\nurl: https://www.coverforce.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: acting in your capacity as an individual or an employee or other representative of your company or other\n    entity, if applicable\n- type: business\n  text: for independent agencies, the CoverForce Independent Agency Customer Agreement; for other customers, the\n    applicable Master Service Agreement and Order Form\nrestricted_uses:\n\
  - summary: Illegal spam\n  text: You are strictly prohibited from using the Website or any of the Company's Services for illegal spam activities\n- summary: Pay-per-click on trademarked terms\n  text: you may not participate in pay-per-click advertising on the Company's trademarked terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/coverforce/eligibility/coverforce-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Coverforce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Commercial Insurance
- Insurance Distribution
- Embedded Insurance
- Underwriting
- Document AI
---
