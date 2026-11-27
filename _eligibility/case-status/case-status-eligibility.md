---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Service is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: individual
  minimum_age:
    text: The Service is intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Text message service opt-in
    text: AGREE TO OPT IN TO THE CASE STATUS TEXT MESSAGE SERVICE (THE “TEXT SERVICE”)
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
name: Case Status
provenance_date: '2026-11-09'
provider_name: Case Status
provider_slug: case-status
slug: case-status-eligibility
source_date: '2026-11-09'
source_filename: case-status-eligibility.yml
source_heading: Eligibility
source_page: https://www.casestatus.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Case Status\naid: case-status\nurl: https://www.casestatus.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Service is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Text message service opt-in\n  text: AGREE TO OPT IN TO THE CASE STATUS TEXT MESSAGE SERVICE (THE “TEXT SERVICE”)\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/case-status/eligibility/case-status-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Case Status's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Client Communication
- Case Management
- Client Portal
- Client Experience
- Artificial Intelligence
- Messaging
- Law Firms
---
