---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: for sale to one or more Users in states where available.
  entity_types:
  - text: The Services are offered for your personal and non-commercial use only
    type: individual
  - text: For business accounts, contract specific terms may apply depending on usage and rate class.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Ohio PIPP or arrearage program participants
    text: This Agreement is not available and would be void for any User who registers with Arbor and the User is currently approved or becomes approved for the percentage of income payment plan (PIPP) or arrearage crediting program.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize Arbor, directly or through third parties, to make any inquiries we consider necessary to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arbor
provenance_date: '2026-11-09'
provider_name: Arbor
provider_slug: arbor
slug: arbor-eligibility
source_date: '2026-11-09'
source_filename: arbor-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinarbor.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arbor\naid: arbor\nurl: https://www.joinarbor.com/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: for sale to one or more Users in states where available.\nentity_types:\n- type: individual\n  text: The Services are offered for your personal and non-commercial use only\n- type: business\n  text: For business accounts, contract specific terms may apply depending on usage and rate class.\nrestricted_uses:\n- summary: Ohio PIPP or arrearage program participants\n  text: This Agreement is not available and would be void for any User who registers with Arbor and the User is\n\
  \    currently approved or becomes approved for the percentage of income payment plan (PIPP) or arrearage crediting\n    program.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize Arbor, directly or through third parties, to make any inquiries we consider necessary to verify\n    your identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arbor/eligibility/arbor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Arbor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Electricity
- Utilities
- Sustainability
- Consumer
- Cost Savings
---
