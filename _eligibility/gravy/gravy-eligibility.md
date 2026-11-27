---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be able to form a legally binding contract and be at least the age required by your jurisdiction to use online services.
    type: individual
  - text: If you use Gravy on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: be at least the age required by your jurisdiction to use online services
    value: null
  restricted_uses:
  - summary: Unlawful consequential decisions
    text: use the service to make unlawful credit, employment, insurance, housing, or eligibility decisions
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
name: Gravy
provenance_date: '2026-11-09'
provider_name: Gravy
provider_slug: gravy
slug: gravy-eligibility
source_date: '2026-11-09'
source_filename: gravy-eligibility.yml
source_heading: Eligibility
source_page: https://gravy.finance/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gravy\naid: gravy\nurl: https://gravy.finance/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be able to form a legally binding contract and be at least the age required by your jurisdiction\n    to use online services.\n- type: business\n  text: If you use Gravy on behalf of an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Unlawful consequential decisions\n  text: use the service to make unlawful credit, employment, insurance, housing, or eligibility decisions\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: be at least the age required by your jurisdiction to use online services\n"
source_yaml_url: https://artifacts.apis.io/gravy/eligibility/gravy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gravy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Finance
- Fintech
- Artificial Intelligence
- Consumer
- Local-First
- Mac
- Financial Management
---
