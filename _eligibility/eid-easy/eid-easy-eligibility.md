---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: “You” – the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: individual
  - text: “Customer” – person of legal entity who uses the Service with the intent of identifying End Users or letting End Users to create electronic signatures.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries and parties
    text: You are not listed on any United States government list of prohibited or restricted parties.
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
name: eID Easy
provenance_date: '2026-11-09'
provider_name: eID Easy
provider_slug: eid-easy
slug: eid-easy-eligibility
source_date: '2026-11-09'
source_filename: eid-easy-eligibility.yml
source_heading: Eligibility
source_page: https://www.eideasy.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eID Easy\naid: eid-easy\nurl: https://www.eideasy.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types:\n- type: individual\n  text: “You” – the individual accessing or using the Service, or the company, or other legal entity on behalf of\n    which such individual is accessing or using the Service, as applicable.\n- type: business\n  text: “Customer” – person of legal entity who uses the Service with the intent of identifying\
  \ End Users or letting\n    End Users to create electronic signatures.\nrestricted_uses:\n- summary: Sanctioned countries and parties\n  text: You are not listed on any United States government list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eid-easy/eligibility/eid-easy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from eID Easy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- eSealing
- eID
- Digital Identity
---
