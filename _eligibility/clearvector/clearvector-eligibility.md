---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer acknowledges and agrees the Offerings shall not be used, transferred, or otherwise exported or re-exported to regions that the United States and/or the European Union maintains an embargo or comprehensive sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed countries and designated nationals
    text: Customer represents and warrants that Customer is not located in, or is under the control of, or a national or resident of, an Embargoed Country or Designated National.
  - summary: Not for safety-critical applications
    text: NEITHER THE OFFERINGS NOR CLEARVECTOR TOOLS ARE FOR USE IN THE OPERATION OF AIRCRAFT NAVIGATION, NUCLEAR FACILITIES, COMMUNICATION SYSTEMS, WEAPONS SYSTEMS, DIRECT OR INDIRECT LIFE-SUPPORT SYSTEMS, AIR TRAFFIC CONTROL
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
name: Clearvector
provenance_date: '2026-11-09'
provider_name: Clearvector
provider_slug: clearvector
slug: clearvector-eligibility
source_date: '2026-11-09'
source_filename: clearvector-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearvector.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearvector\naid: clearvector\nurl: https://www.clearvector.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer acknowledges and agrees the Offerings shall not be used, transferred, or otherwise exported or\n    re-exported to regions that the United States and/or the European Union maintains an embargo or comprehensive\n    sanctions\nentity_types: []\nrestricted_uses:\n- summary: Embargoed countries and designated nationals\n  text: Customer represents and warrants that Customer is not located in, or is under the control of, or a national\n    or resident of, an\
  \ Embargoed Country or Designated National.\n- summary: Not for safety-critical applications\n  text: NEITHER THE OFFERINGS NOR CLEARVECTOR TOOLS ARE FOR USE IN THE OPERATION OF AIRCRAFT NAVIGATION, NUCLEAR\n    FACILITIES, COMMUNICATION SYSTEMS, WEAPONS SYSTEMS, DIRECT OR INDIRECT LIFE-SUPPORT SYSTEMS, AIR TRAFFIC CONTROL\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearvector/eligibility/clearvector-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Clearvector's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cloud Security
- Detection and Response
- Identity
- Threat Detection
- Incident Response
- Cloud
---
