---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to participate in The Fiix Community.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to participate in The Fiix Community.
    value: '18'
  restricted_uses:
  - summary: No promotion of third-party services
    text: The Fiix Community is provided as a service to Fiix customers and is not intended for the promotion of third-party services, products, websites, or organizations.
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
name: Fiix Software
provenance_date: '2026-11-09'
provider_name: Fiix Software
provider_slug: fiix-software
slug: fiix-software-eligibility
source_date: '2026-11-09'
source_filename: fiix-software-eligibility.yml
source_heading: Eligibility
source_page: https://community.fiixsoftware.com/site/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fiix Software\naid: fiix-software\nurl: https://community.fiixsoftware.com/site/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to participate in The Fiix Community.\nrestricted_uses:\n- summary: No promotion of third-party services\n  text: The Fiix Community is provided as a service to Fiix customers and is not intended for the promotion of third-party\n    services, products, websites, or organizations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old to participate in The Fiix Community.\n"
source_yaml_url: https://artifacts.apis.io/fiix-software/eligibility/fiix-software-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fiix Software's own page on 2026-11-09.
synthetic: false
tags:
- CMMS
- Maintenance Management
- Asset Management
- Manufacturing
- Reliability
- Work Orders
- Software-as-a-Service
---
