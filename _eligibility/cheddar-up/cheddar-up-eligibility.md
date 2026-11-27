---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To use the Services or access the Platform, You must be a resident of the United States or one of its territories
  entity_types:
  - text: You must be at least 18 years old or the age of majority in Your state of residence.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older. If You are a minor under the age of 18, You may only use the Platform in conjunction with Your parents or guardians.
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent collections
    text: Organizers may only set up Collections for legal purposes.
  - summary: Debt collection
    text: The Services may not be used for debt collection activities as defined by Applicable Law
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 'We may, in Our discretion: (i) further validate Your identity by reviewing Your identification documents'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cheddar Up
provenance_date: '2026-11-09'
provider_name: Cheddar Up
provider_slug: cheddar-up
slug: cheddar-up-eligibility
source_date: '2026-11-09'
source_filename: cheddar-up-eligibility.yml
source_heading: Eligibility
source_page: https://www.cheddarup.com/privacy-terms/?copyReq=terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cheddar Up\naid: cheddar-up\nurl: https://www.cheddarup.com/privacy-terms/?copyReq=terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To use the Services or access the Platform, You must be a resident of the United States or one of its territories\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in Your state of residence.\nrestricted_uses:\n- summary: Illegal or fraudulent collections\n  text: Organizers may only set up Collections for legal purposes.\n- summary: Debt collection\n  text: The Services may not be used for\
  \ debt collection activities as defined by Applicable Law\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 'We may, in Our discretion: (i) further validate Your identity by reviewing Your identification documents'\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older. If You are a minor under the age of 18, You may only use the Platform\n    in conjunction with Your parents or guardians.\n"
source_yaml_url: https://artifacts.apis.io/cheddar-up/eligibility/cheddar-up-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cheddar Up's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Group Payments
- Fundraising
- Non-Profit
- Schools
- Forms
- Fintech
- Payment Collection
---
