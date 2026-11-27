---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: Services are available only to, and may only be used by, individuals who are 18 years and older
    value: '18'
  restricted_uses:
  - summary: Void where prohibited
    text: This provision is void where prohibited by law and the right to access the Services is revoked in those jurisdictions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may, in its sole discretion, refuse to offer access to or use of the Services to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LawnStarter
provenance_date: '2026-11-09'
provider_name: LawnStarter
provider_slug: lawnstarter
slug: lawnstarter-eligibility
source_date: '2026-11-09'
source_filename: lawnstarter-eligibility.yml
source_heading: Eligibility
source_page: https://www.lawnstarter.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawnStarter\naid: lawnstarter\nurl: https://www.lawnstarter.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Services are available only to, and may only be used by, individuals who are 18 years and older who can\n    form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Void where prohibited\n  text: This provision is void where prohibited by law and the right to access the Services is revoked in those\n    jurisdictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Company may, in its sole discretion, refuse to offer access to or use of the Services to any person or entity\n    and change its eligibility criteria at any time.\nminimum_age:\n  value: '18'\n  text: Services are available only to, and may only be used by, individuals who are 18 years and older\n"
source_yaml_url: https://artifacts.apis.io/lawnstarter/eligibility/lawnstarter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LawnStarter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lawn Care
- Landscaping
- Home Services
- Marketplace
- On-Demand
- Local Services
---
