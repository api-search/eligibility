---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: use the Corsha IdP Software system and SaaS platform solely for the legitimate business purposes of the Customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: export, or take any action that would be a “deemed export,” as defined by U.S. export control laws, of any of Corsha’s Software or proprietary information, without the express written consent of Corsha
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
name: Corsha
provenance_date: '2026-11-09'
provider_name: Corsha
provider_slug: corsha
slug: corsha-eligibility
source_date: '2026-11-09'
source_filename: corsha-eligibility.yml
source_heading: Eligibility
source_page: https://corsha.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corsha\naid: corsha\nurl: https://corsha.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: use the Corsha IdP Software system and SaaS platform solely for the legitimate business purposes of the\n    Customer\nrestricted_uses:\n- summary: Export restrictions\n  text: export, or take any action that would be a “deemed export,” as defined by U.S. export control laws, of any\n    of Corsha’s Software or proprietary information, without the express written consent of Corsha\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corsha/eligibility/corsha-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Corsha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Industrial
- Identity
- OT
---
