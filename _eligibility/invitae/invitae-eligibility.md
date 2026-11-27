---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from jurisdictions where the contents of our Websites are illegal or penalized is prohibited.
  entity_types:
  - text: You are not obligated to register with Invitae in order to access our Websites.
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Tests ordered only by healthcare providers
    text: Tests available for requisition can only be ordered by an authorized healthcare provider.
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
name: Invitae
provenance_date: '2026-11-09'
provider_name: Invitae
provider_slug: invitae
slug: invitae-eligibility
source_date: '2026-11-09'
source_filename: invitae-eligibility.yml
source_heading: Eligibility
source_page: https://www.invitae.com/us/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invitae\naid: invitae\nurl: https://www.invitae.com/us/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from jurisdictions where the contents of our Websites are illegal or penalized is prohibited.\nentity_types:\n- type: individual\n  text: You are not obligated to register with Invitae in order to access our Websites.\nrestricted_uses:\n- summary: Tests ordered only by healthcare providers\n  text: Tests available for requisition can only be ordered by an authorized healthcare provider.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/invitae/eligibility/invitae-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Invitae's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Genomics
- Genetic Testing
- Precision Medicine
- Life Sciences
- Diagnostics
- Clinical Laboratory
- Oncology
- Rare Disease
---
