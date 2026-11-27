---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service.
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: No employee, independent contractor, agent, or affiliate of any competing residential home maintenance and management company is permitted to view, access, or use any portion of the Service without express written permission from Honey Homes.
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
name: Honeyhomes
provenance_date: '2026-11-09'
provider_name: Honeyhomes
provider_slug: honeyhomes
slug: honeyhomes-eligibility
source_date: '2026-11-09'
source_filename: honeyhomes-eligibility.yml
source_heading: Eligibility
source_page: https://www.honeyhomes.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Honeyhomes\naid: honeyhomes\nurl: https://www.honeyhomes.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service.\nrestricted_uses:\n- summary: Competitors\n  text: No employee, independent contractor, agent, or affiliate of any competing residential home maintenance and\n    management company is permitted to view, access, or use any portion of the Service without express written permission\n    from Honey Homes.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/honeyhomes/eligibility/honeyhomes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Honeyhomes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Home Maintenance
- Handyman
- Property Management
- Membership
- Consumer Services
- Real Estate
---
