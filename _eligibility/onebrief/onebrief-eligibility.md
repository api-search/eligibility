---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using our Services for an organization, you're agreeing to these Terms on behalf of that organization.
    type: business
  minimum_age:
    text: You are responsible for determining the age of digital consent under your local law. If you don't meet these age requirements, you agree not to use the Services.
    value: null
  restricted_uses:
  - summary: Security clearance and CUI compliance
    text: Users who add other users to a plan or planning team acknowledge and agree that they are solely responsible for ensuring team members have appropriate clearance access and need to know
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
name: Onebrief
provenance_date: '2026-11-10'
provider_name: Onebrief
provider_slug: onebrief
slug: onebrief-eligibility
source_date: '2026-11-10'
source_filename: onebrief-eligibility.yml
source_heading: Eligibility
source_page: https://www.onebrief.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onebrief\naid: onebrief\nurl: https://www.onebrief.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're using our Services for an organization, you're agreeing to these Terms on behalf of that organization.\nrestricted_uses:\n- summary: Security clearance and CUI compliance\n  text: Users who add other users to a plan or planning team acknowledge and agree that they are solely responsible\n    for ensuring team members have appropriate clearance access and need to know\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are responsible for determining the age of digital consent under your local law. If you don't meet these\n    age requirements, you agree not to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/onebrief/eligibility/onebrief-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Onebrief's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Defense
- Military
- Command and Control
- Decision Intelligence
- Planning
- Collaboration
- Data Interoperability
- JADC2
- Artificial Intelligence
---
