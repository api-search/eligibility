---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Subscriber” or “you” means the entity that has agreed to be bound by these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or benchmarking use
    text: (vi) access or use (or permit a third party to access or use) the Services for any unlawful purpose or for purposes of monitoring the availability, performance or functionality of the Services or for any other benchmarking or competitive purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Joyful Health may choose not to accept Orders at its sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Joyful
provenance_date: '2026-11-09'
provider_name: Joyful
provider_slug: joyful
slug: joyful-eligibility
source_date: '2026-11-09'
source_filename: joyful-eligibility.yml
source_heading: Eligibility
source_page: https://www.joyfulhealth.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Joyful\naid: joyful\nurl: https://www.joyfulhealth.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Subscriber” or “you” means the entity that has agreed to be bound by these Terms.\nrestricted_uses:\n- summary: Unlawful or benchmarking use\n  text: (vi) access or use (or permit a third party to access or use) the Services for any unlawful purpose or for\n    purposes of monitoring the availability, performance or functionality of the Services or for any other benchmarking\n    or competitive purposes\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: Joyful Health may choose not to accept Orders at its sole and absolute discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/joyful/eligibility/joyful-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Joyful's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Revenue Cycle Management
- Medical Billing
- Claims
- Denial Management
- Artificial Intelligence
- Healthcare Finance
---
