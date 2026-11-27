---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Chargezoom will require that you provide specific information about yourself and/or your business.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unauthorized access to non-public areas
    text: Except with the written permission of Chargezoom, you agree that you will not access or attempt to access password protected, secure or non-public areas of the Chargezoom Web Site.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Chargezoom reserves the right to reject any registration for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chargezoom
provenance_date: '2026-11-09'
provider_name: Chargezoom
provider_slug: chargezoom
slug: chargezoom-eligibility
source_date: '2026-11-09'
source_filename: chargezoom-eligibility.yml
source_heading: Eligibility
source_page: https://www.chargezoom.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chargezoom\naid: chargezoom\nurl: https://www.chargezoom.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Chargezoom will require that you provide specific information about yourself and/or your business.\nrestricted_uses:\n- summary: No unauthorized access to non-public areas\n  text: Except with the written permission of Chargezoom, you agree that you will not access or attempt to access\n    password protected, secure or non-public areas of the Chargezoom Web Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Chargezoom reserves the right to reject any registration for any reason.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chargezoom/eligibility/chargezoom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Chargezoom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Automation
- Artificial Intelligence
---
