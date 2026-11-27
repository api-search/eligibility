---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer executing or otherwise accepting the Order Form which refer to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Customer is not located and does not and will not use, export, re-export or import the Service (or any portion thereof) in or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls
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
name: Joon
provenance_date: '2026-11-09'
provider_name: Joon
provider_slug: joon
slug: joon-eligibility
source_date: '2026-11-09'
source_filename: joon-eligibility.yml
source_heading: Eligibility
source_page: https://joon.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Joon\naid: joon\nurl: https://joon.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer executing or otherwise accepting the Order Form which refer to these Terms\nrestricted_uses:\n- summary: Export control compliance\n  text: Customer is not located and does not and will not use, export, re-export or import the Service (or any portion\n    thereof) in or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/joon/eligibility/joon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Joon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cybersecurity
- SOC
- Automation
---
