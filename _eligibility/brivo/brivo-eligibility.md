---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: These Terms of Use are void where prohibited by law and the right to access the Brivo Sites is revoked in such jurisdictions.
  entity_types:
  - text: You must be at least eighteen (18) years old to have a Brivo Account which makes you eligible to access certain of the Brivo Sites.
    type: individual
  - text: if you are an authorized Brivo reseller, the terms and conditions of your reseller agreement with Brivo.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to have a Brivo Account which makes you eligible to access certain of the Brivo Sites.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Brivo reserves the right to refuse access to certain Brivo Sites or portions thereof to anyone, at any time, without notice, and for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brivo
provenance_date: '2026-11-09'
provider_name: Brivo
provider_slug: brivo
slug: brivo-eligibility
source_date: '2026-11-09'
source_filename: brivo-eligibility.yml
source_heading: Eligibility
source_page: https://explore.brivo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brivo\naid: brivo\nurl: https://explore.brivo.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: These Terms of Use are void where prohibited by law and the right to access the Brivo Sites is revoked in\n    such jurisdictions.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to have a Brivo Account which makes you eligible to access\n    certain of the Brivo Sites.\n- type: business\n  text: if you are an authorized Brivo reseller, the terms and conditions of your reseller agreement with Brivo.\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Brivo reserves the right to refuse access to certain Brivo Sites or portions thereof to anyone, at any time,\n    without notice, and for any reason.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to have a Brivo Account which makes you eligible to access\n    certain of the Brivo Sites.\n"
source_yaml_url: https://artifacts.apis.io/brivo/eligibility/brivo-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Brivo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Access Control
- Video Surveillance
- Cloud
---
