---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"User" means any individual who accesses or uses the Application to perform or be matched for Services, regardless of whether the Services are provided on an independent contractor basis or as an employee of Traba or a Traba affiliate.'
    type: individual
  - text: If You are accessing and using the Services on behalf of a company (such as Your employer) or other legal entity, You represent and warrant that You have the authority to bind that company or other legal entity to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: User agrees to comply with all applicable laws when using the Application, and User may only use the Application for lawful purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Subject to a satisfactory background check and agreement to the terms herein, User will be eligible to use the Application to view and accept Customer Requests.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Traba
provenance_date: '2026-11-10'
provider_name: Traba
provider_slug: traba
slug: traba-eligibility
source_date: '2026-11-10'
source_filename: traba-eligibility.yml
source_heading: Eligibility
source_page: https://traba.work/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Traba\naid: traba\nurl: https://traba.work/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"User\" means any individual who accesses or uses the Application to perform or be matched for Services,\n    regardless of whether the Services are provided on an independent contractor basis or as an employee of Traba\n    or a Traba affiliate.'\n- type: business\n  text: If You are accessing and using the Services on behalf of a company (such as Your employer) or other legal\n    entity, You represent and warrant that You have\
  \ the authority to bind that company or other legal entity to\n    this Agreement.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: User agrees to comply with all applicable laws when using the Application, and User may only use the Application\n    for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Subject to a satisfactory background check and agreement to the terms herein, User will be eligible to use\n    the Application to view and accept Customer Requests.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/traba/eligibility/traba-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Traba's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Staffing
- Workforce
- Supply Chain
- Logistics
- Warehouse
- Artificial Intelligence
---
