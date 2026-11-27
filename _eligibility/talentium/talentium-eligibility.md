---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" – means the business customer accepting these Terms & Conditions or as identified in an order form.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer use excluded
    text: this Agreement does not apply to consumers and the Platform may only be used for professional business purposes.
  - summary: Sensitive personal data
    text: The Customer undertakes not to include and process sensitive personal data within the Services
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
name: Talentium
provenance_date: '2026-11-10'
provider_name: Talentium
provider_slug: talentium
slug: talentium-eligibility
source_date: '2026-11-10'
source_filename: talentium-eligibility.yml
source_heading: Eligibility
source_page: https://talentium.io/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Talentium\naid: talentium\nurl: https://talentium.io/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Customer\" – means the business customer accepting these Terms & Conditions or as identified in an order\n    form.'\nrestricted_uses:\n- summary: Consumer use excluded\n  text: this Agreement does not apply to consumers and the Platform may only be used for professional business purposes.\n- summary: Sensitive personal data\n  text: The Customer undertakes not to include and process sensitive personal data\
  \ within the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/talentium/eligibility/talentium-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Talentium's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Recruiting
- Hiring
- Human Resources
- Talent Acquisition
- Candidate Sourcing
- Applicant Tracking
---
