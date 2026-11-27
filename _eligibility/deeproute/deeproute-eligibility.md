---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A parent or legal guardian must submit the application, agree to these Terms, and act as the account holder, including for athletes who are 18 or older.
    type: individual
  minimum_age:
    text: DeepRoute is for athletes who are at least a sophomore in high school.
    value: null
  restricted_uses:
  - summary: Football only, high school athletes
    text: DeepRoute is for athletes who are at least a sophomore in high school.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We review each application and may decline it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Deeproute
provenance_date: '2026-11-09'
provider_name: Deeproute
provider_slug: deeproute
slug: deeproute-eligibility
source_date: '2026-11-09'
source_filename: deeproute-eligibility.yml
source_heading: Eligibility
source_page: https://www.deeproute.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deeproute\naid: deeproute\nurl: https://www.deeproute.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A parent or legal guardian must submit the application, agree to these Terms, and act as the account holder,\n    including for athletes who are 18 or older.\nrestricted_uses:\n- summary: Football only, high school athletes\n  text: DeepRoute is for athletes who are at least a sophomore in high school.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We review each application and may decline\
  \ it.\nminimum_age:\n  value: null\n  text: DeepRoute is for athletes who are at least a sophomore in high school.\n"
source_yaml_url: https://artifacts.apis.io/deeproute/eligibility/deeproute-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Deeproute's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Outreach
- Sports
- Recruiting
- Education
---
