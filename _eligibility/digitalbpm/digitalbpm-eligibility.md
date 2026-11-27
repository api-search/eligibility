---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users aren't located in a country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a 'terrorist-supporting' country
  entity_types:
  - text: Indicates any natural person or legal entity using DigitalBPM Platform.
    type: individual
  - text: Business User Any User that does not qualify as a Consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: Users are solely responsible for making sure that their use of DigitalBPM Platform and/or the Service violates no applicable law, regulations or third-party rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service Users must register or create a User account, providing all required data or information in a complete and truthful manner.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DigitalBPM
provenance_date: '2026-11-09'
provider_name: DigitalBPM
provider_slug: digitalbpm
slug: digitalbpm-eligibility
source_date: '2026-11-09'
source_filename: digitalbpm-eligibility.yml
source_heading: Eligibility
source_page: https://digitalbpm.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DigitalBPM\naid: digitalbpm\nurl: https://digitalbpm.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users aren't located in a country that is subject to a U.S. government embargo, or that has been designated\n    by the U.S. government as a 'terrorist-supporting' country\nentity_types:\n- type: individual\n  text: Indicates any natural person or legal entity using DigitalBPM Platform.\n- type: business\n  text: Business User Any User that does not qualify as a Consumer.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: Users are solely responsible\
  \ for making sure that their use of DigitalBPM Platform and/or the Service violates\n    no applicable law, regulations or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service Users must register or create a User account, providing all required data or information\n    in a complete and truthful manner.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digitalbpm/eligibility/digitalbpm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from DigitalBPM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- No-Code
- Software-as-a-Service
- Integration
---
