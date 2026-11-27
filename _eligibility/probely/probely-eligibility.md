---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms or using the Services on behalf of an organization, you are agreeing to these Terms for that organization and representing to us that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harmful or unlawful use
    text: You must not use the Service to harm, threaten, or harass another person, organization, or Probely, S.A.
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
name: Probely
provenance_date: '2026-11-10'
provider_name: Probely
provider_slug: probely
slug: probely-eligibility
source_date: '2026-11-10'
source_filename: probely-eligibility.yml
source_heading: Eligibility
source_page: https://dev.probely.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Probely\naid: probely\nurl: https://dev.probely.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms or using the Services on behalf of an organization, you are agreeing to\n    these Terms for that organization and representing to us that you have the authority to bind that organization\n    to these Terms\nrestricted_uses:\n- summary: Harmful or unlawful use\n  text: You must not use the Service to harm, threaten, or harass another person, organization, or Probely, S.A.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/probely/eligibility/probely-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Probely's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
