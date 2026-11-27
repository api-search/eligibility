---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Site from territories where its contents are illegal is prohibited.
  entity_types:
  - text: The Site is available only to users who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Site is available only to users who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: unlawful or damaging use
    text: you will not use the Site for any purpose that is unlawful or prohibited by this Agreement. You may not use the Site in any manner that, in our sole discretion, could damage, disable, overburden, or impair it
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
name: Ancora Heart
provenance_date: '2026-11-09'
provider_name: Ancora Heart
provider_slug: ancora-heart
slug: ancora-heart-eligibility
source_date: '2026-11-09'
source_filename: ancora-heart-eligibility.yml
source_heading: Eligibility
source_page: https://www.ancoraheart.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ancora Heart\naid: ancora-heart\nurl: https://www.ancoraheart.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Site from territories where its contents are illegal is prohibited.\nentity_types:\n- type: individual\n  text: The Site is available only to users who are at least 13 years old.\nrestricted_uses:\n- summary: unlawful or damaging use\n  text: you will not use the Site for any purpose that is unlawful or prohibited by this Agreement. You may not\n    use the Site in any manner that, in our sole discretion, could damage, disable, overburden,\
  \ or impair it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is available only to users who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/ancora-heart/eligibility/ancora-heart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ancora Heart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Cardiology
- Heart Failure
- Clinical Trials
- Transcatheter Therapy
- Medical Technology
---
