---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region, or jurisdiction.
  entity_types:
  - text: teachers and school administrators
    type: business
  minimum_age:
    text: Every Account must have one designated Adult User who must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use of Content prohibited
    text: for your personal, non-commercial use only
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
name: Lingokids
provenance_date: '2026-11-09'
provider_name: Lingokids
provider_slug: lingokids
slug: lingokids-eligibility
source_date: '2026-11-09'
source_filename: lingokids-eligibility.yml
source_heading: Eligibility
source_page: https://lingokids.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lingokids\naid: lingokids\nurl: https://lingokids.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region, or jurisdiction.\nentity_types:\n- type: business\n  text: teachers and school administrators\nrestricted_uses:\n- summary: Commercial use of Content prohibited\n  text: for your personal, non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: Every Account must have one designated Adult User who must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/lingokids/eligibility/lingokids-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lingokids's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- Children
- Language Learning
- Mobile App
- Spain
---
