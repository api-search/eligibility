---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual or organization that accesses or uses the Service
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Regulated advice via AI
    text: provide regulated advice without required licenses and professional review
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
name: Capital Workbench
provenance_date: '2026-11-09'
provider_name: Capital Workbench
provider_slug: capital-workbench-com
slug: capital-workbench-com-eligibility
source_date: '2026-11-09'
source_filename: capital-workbench-com-eligibility.yml
source_heading: Eligibility
source_page: https://capital-workbench.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capital Workbench\naid: capital-workbench-com\nurl: https://capital-workbench.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual or organization that accesses or uses the Service\nrestricted_uses:\n- summary: Regulated advice via AI\n  text: provide regulated advice without required licenses and professional review\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/capital-workbench-com/eligibility/capital-workbench-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Capital Workbench's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Analytics
- Public Companies
- Data
- Platform
---
