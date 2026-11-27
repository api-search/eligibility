---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have legal authority to bind that entity to the Terms.
    type: business
  minimum_age:
    text: You may only access the APIs if you are of legal age to form a binding contract with Empower.
    value: null
  restricted_uses:
  - summary: Unlawful transactions
    text: Promote or facilitate unlawful transactions.
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
name: Great-West Lifeco
provenance_date: '2026-11-09'
provider_name: Great-West Lifeco
provider_slug: great-west-lifeco
slug: great-west-lifeco-eligibility
source_date: '2026-11-09'
source_filename: great-west-lifeco-eligibility.yml
source_heading: Eligibility
source_page: https://developer.empower.com/DevTerms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Great-West Lifeco\naid: great-west-lifeco\nurl: https://developer.empower.com/DevTerms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have legal authority\n    to bind that entity to the Terms.\nrestricted_uses:\n- summary: Unlawful transactions\n  text: Promote or facilitate unlawful transactions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may only access the APIs if you\
  \ are of legal age to form a binding contract with Empower.\n"
source_yaml_url: https://artifacts.apis.io/great-west-lifeco/eligibility/great-west-lifeco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Great-West Lifeco's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Life Insurance
- Health Insurance
- Employee Benefits
- Retirement
- Wealth Management
- Reinsurance
- Annuities
---
