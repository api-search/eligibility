---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Jurisdiction-Specific Terms: United States Brazil Poland, France, Romania India Indonesia. Use of the Brainly Services and Brainly Subscriptions is void where prohibited.'
  entity_types:
  - text: By accessing or using the Brainly Services or Brainly Subscription or purchasing a Brainly Subscription, you represent and warrant that you are of legal age in your jurisdiction and otherwise have the capacity to form a binding legal agreement with Brainly.
    type: individual
  minimum_age:
    text: Children under the age of 13 may only access or use the Brainly Services through a designated child account created, managed, and authorized by a verified parent or legal guardian
    value: '13'
  restricted_uses:
  - summary: Child accounts only for own children
    text: Parent Account Holders are strictly prohibited from creating or linking Child Accounts for individuals who are not their legal children or wards.
  - summary: Under-13 direct registration prohibited (US)
    text: Direct registration by children under the age of 13 is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Brainly requires Verifiable Parental Consent prior to account activation in accordance with 16 C.F.R. Part 312.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brainly
provenance_date: '2026-11-09'
provider_name: Brainly
provider_slug: brainly
slug: brainly-eligibility
source_date: '2026-11-09'
source_filename: brainly-eligibility.yml
source_heading: Eligibility
source_page: https://brainly.com/pages/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brainly\naid: brainly\nurl: https://brainly.com/pages/terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Jurisdiction-Specific Terms: United States Brazil Poland, France, Romania India Indonesia. Use of the Brainly\n    Services and Brainly Subscriptions is void where prohibited.'\nentity_types:\n- type: individual\n  text: By accessing or using the Brainly Services or Brainly Subscription or purchasing a Brainly Subscription,\n    you represent and warrant that you are of legal age in your jurisdiction and otherwise have the capacity to\n    form a\
  \ binding legal agreement with Brainly.\nrestricted_uses:\n- summary: Child accounts only for own children\n  text: Parent Account Holders are strictly prohibited from creating or linking Child Accounts for individuals who\n    are not their legal children or wards.\n- summary: Under-13 direct registration prohibited (US)\n  text: Direct registration by children under the age of 13 is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Brainly requires Verifiable Parental Consent prior to account activation in accordance with 16 C.F.R. Part\n    312.\nminimum_age:\n  value: '13'\n  text: Children under the age of 13 may only access or use the Brainly Services through a designated child account\n    created, managed, and authorized by a verified parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/brainly/eligibility/brainly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Brainly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- Learning
- Homework Help
- AI Tutor
- Community
---
