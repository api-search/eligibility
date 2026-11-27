---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are only available in jurisdictions supported by Gilion.
  entity_types:
  - text: the company that registered for the Platform as Platform Customer, or (ii) the company that registered for the Platform as Capital Partner
    type: business
  - text: The individual that registers for the use of the Platform must at all times comply with the User Rules set out below.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited or high-risk AI uses
    text: The Customer shall not use the Platform for any purpose which would constitute Prohibited AI or High Risk AI under the EU AI Act, or which is otherwise prohibited or unlawful.
  - summary: Sanctioned persons
    text: ensure that it shall not supply any goods or other items pursuant to this Agreement from, or on behalf of, a “ Restricted Person ”
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Capital Partner will be onboarded to the Platform based on a classification process that evaluates their intended use, resources and operational needs.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gilion (formerly ArK)
provenance_date: '2026-11-09'
provider_name: Gilion (formerly ArK)
provider_slug: gilion-formerly-ark
slug: gilion-formerly-ark-eligibility
source_date: '2026-11-09'
source_filename: gilion-formerly-ark-eligibility.yml
source_heading: Eligibility
source_page: https://www.gilion.com/terms/en-global-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gilion (formerly ArK)\naid: gilion-formerly-ark\nurl: https://www.gilion.com/terms/en-global-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are only available in jurisdictions supported by Gilion.\nentity_types:\n- type: business\n  text: the company that registered for the Platform as Platform Customer, or (ii) the company that registered for\n    the Platform as Capital Partner\n- type: individual\n  text: The individual that registers for the use of the Platform must at all times comply with the User Rules set\n    out below.\nrestricted_uses:\n- summary: Prohibited\
  \ or high-risk AI uses\n  text: The Customer shall not use the Platform for any purpose which would constitute Prohibited AI or High Risk\n    AI under the EU AI Act, or which is otherwise prohibited or unlawful.\n- summary: Sanctioned persons\n  text: ensure that it shall not supply any goods or other items pursuant to this Agreement from, or on behalf of,\n    a “ Restricted Person ”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Capital Partner will be onboarded to the Platform based on a classification process that evaluates their\n    intended use, resources and operational needs.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gilion-formerly-ark/eligibility/gilion-formerly-ark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Gilion (formerly ArK)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Growth Financing
- Venture Debt
- Artificial Intelligence
- Investment
- Software-as-a-Service
---
