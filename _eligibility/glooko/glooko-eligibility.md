---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You are not (a) located in, or a resident or a national of, any country subject to a United States government embargo or other restriction or any country that has been designated by the United States government as a "terrorist supporting" country
  entity_types:
  - text: The Services are available only to individuals who are adults, or children whose use is supervised by a parent and/or legal guardian.
    type: individual
  minimum_age:
    text: The Services are available only to individuals who are adults, or children whose use is supervised by a parent and/or legal guardian.
    value: null
  restricted_uses:
  - summary: Medical advice reliance
    text: The Services are not intended to provide treatment decisions or to be used as a substitute for professional healthcare advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Glooko
provenance_date: '2026-11-09'
provider_name: Glooko
provider_slug: glooko
slug: glooko-eligibility
source_date: '2026-11-09'
source_filename: glooko-eligibility.yml
source_heading: Eligibility
source_page: https://glooko.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Glooko\naid: glooko\nurl: https://glooko.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You are not (a) located in, or a resident or a national of, any country subject to a United States government\n    embargo or other restriction or any country that has been designated by the United States government as a \"terrorist\n    supporting\" country\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who are adults, or children whose use is supervised by a\n    parent and/or legal guardian.\n\
  restricted_uses:\n- summary: Medical advice reliance\n  text: The Services are not intended to provide treatment decisions or to be used as a substitute for professional\n    healthcare advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The Services are available only to individuals who are adults, or children whose use is supervised by a\n    parent and/or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/glooko/eligibility/glooko-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Glooko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Diabetes
- Diabetes Management
- Healthcare
- Digital Health
- Remote Patient Monitoring
- Medical Devices
- EHR Integration
- FHIR
- Interoperability
- Chronic Care
- Life Sciences
---
