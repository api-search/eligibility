---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you create an account or use the Platform on behalf of an individual other than yourself, you represent that you are authorized by such individual or entity
    type: individual
  minimum_age:
    text: The Platform and Services are intended to be accessed solely for persons who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: No commercial or non-personal use
    text: use the Platform for any commercial or non-personal purposes, including any usage which generates any revenues, whether directly or indirectly (other than under your Account), without our prior written consent
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Air Doctor may, but is not obligated to, perform verification of any submitted information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Air Doctor
provenance_date: '2026-11-09'
provider_name: Air Doctor
provider_slug: air-doctor
slug: air-doctor-eligibility
source_date: '2026-11-09'
source_filename: air-doctor-eligibility.yml
source_heading: Eligibility
source_page: https://air-dr.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Air Doctor\naid: air-doctor\nurl: https://air-dr.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you create an account or use the Platform on behalf of an individual other than yourself, you represent\n    that you are authorized by such individual or entity\nrestricted_uses:\n- summary: No commercial or non-personal use\n  text: use the Platform for any commercial or non-personal purposes, including any usage which generates any revenues,\n    whether directly or indirectly (other than under your Account), without\
  \ our prior written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Air Doctor may, but is not obligated to, perform verification of any submitted information.\nminimum_age:\n  value: '18'\n  text: The Platform and Services are intended to be accessed solely for persons who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/air-doctor/eligibility/air-doctor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Air Doctor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Telehealth
- Healthcare
- Travel
- Travel Insurance
- Medical Services
- Health Tech
---
